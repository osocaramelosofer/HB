<template>
  <div class="flip-card">
    <div class="flip-card-inner">
      <div class="flip-card-front">
        <img :src="require(`@/assets/${image}`)" alt="Avatar">
      </div>
      <div class="flip-card-back">
        <h2 class="card__title"><span>{{ title }}:</span> The plants are green, the sky is blue, & I'm crazy for you.</h2>
        <p class="date" v-if="created_at">Together since {{ created_at }}👦💙👧</p>
        <div class="publish__container">
          <i>X</i>
          <p class="publisher__name">Sohal Welnab</p>
        </div>
        <p v-if="description">{{ description }}</p>
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
    created_at: String,
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
.flip-card-front img {
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