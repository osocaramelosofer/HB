<template>
  <div class="flip-card">
    <div class="flip-card-inner">
      <div class="flip-card-front">
        <img :src="require(`@/assets/${image}`)" alt="Avatar" class="photo">
      </div>
      <div class="flip-card-back">
        <div class="photo-container">
          <img :src="require(`@/assets/${image2}`)" alt="Avatar" class="photo">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardComponent',
  props: {
    image: String,
    title: String,
    image2: String,
    description: String
  },
  mounted() {
    console.log('image ',this.image)
  }
}
</script>

<style lang="css">

.flip-card {
  width: 250px;
  height: 250px;
  background-color: transparent;
  perspective: 1000px;

  padding: 10px;
  padding-bottom: 90px;
  border-radius: 3px;
  margin:auto;
  /* align-self: center; */

}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: #bbb;
  color: black;
}
.photo-container {
  position: relative;
  width: 250px;
  height: 250px;
}
.photo {
  width: 100%;
  height: 100%;
  object-fit: cover;
}


.flip-card-back {
  background-color: #2980b9;
  color: white;
  transform: rotateY(180deg);
}
</style>