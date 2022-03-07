<template>
  <div class="container">
    <card-component 
      title="Fernando"
      image="1.jpg"
      image2="t1.jpg"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="2"
      image="playita.jpg"
      image2="t2.jpg"
    />
    <card-component 
      title="Fernando"
      image="3.jpg"
      image2="t3.jpg"
    />
    <card-component 
      title="Fernando"
      image="4.jpg"
      image2="t4.jpg"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="5.jpg"
      image2="t5.jpg"
    />
    <card-component 
      title="Fernando"
      image="6.jpg"
      image2="t13.jpg"
    />
    <card-component 
      title="Fernando"
      image="7.jpg"
      image2="t7.jpg"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="8.jpg"
      image2="t8.jpg"
    />
    <card-component 
      title="Fernando"
      image="9.jpg"
      image2="t9.jpg"
    />
    <card-component 
      title="Fernando"
      image="11.jpg"
      image2="t10.jpg"
    />
    <card-component 
      title="Fernando"
      image="12.jpg"
      image2="t11.jpg"
    />
    <card-component 
      title="Fernando"
      image="13.jpg"
      image2="t12.jpg"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="14.jpg"
      image2="t14.jpeg"
    />
    <card-component 
      title="Fernando"
      image="15.jpg"
      image2="t15.jpg"
    />
    <card-component 
      title="Fernando"
      image="16.jpg"
      image2="t16.jpg"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="17.jpg"
      image2="t17.jpg"
    />
    <card-component 
      title="Fernando"
      image="18.jpg"
      image2="t24.jpeg"
    />
    <card-component 
      title="Fernando"
      image="19.jpg"
      image2="t18.jpg"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="20.jpg"
      image2="t19.jpg"
    />
    <card-component 
      title="Fernando"
      image="21.jpg"
      image2="t20.jpg"
    />
    <card-component 
      title="Fernando"
      image="22.jpg"
      image2="t21.jpg"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="23.jpg"
      image2="t22.jpeg"
    />
    <card-component 
      title="Fernando"
      image="24.jpg"
      image2="t23.jpg"
    />
  </div>
</template>

<script>
import CardComponent from './Card.vue'

export default {
  name: "MosaicoComponent",
  components: {
    CardComponent,
  }
};
</script>

<style scoped>
.container {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-template-rows: repeat(3, 1fr);
  column-gap: 5px;
  padding: 40px;
}

@media (max-width: 600px) {
  .container {
    align-items: center;
    justify-content: center;
    grid-template-columns: 1fr;
    grid-template-rows: auto;
  }
}
</style>