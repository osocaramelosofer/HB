<template>
  <div class="container">
    <card-component 
      title="Fernando"
      image="1.jpg"
      created_at="2017"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="2"
      image="playita.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="3.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="4.jpg"
      created_at="2017"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="5.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="6.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="7.jpg"
      created_at="2017"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="8.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="9.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="10.jpg"
      created_at="2017"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="11.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="12.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="13.jpg"
      created_at="2017"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="14.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="15.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="16.jpg"
      created_at="2017"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="17.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="18.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="19.jpg"
      created_at="2017"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="20.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="21.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="22.jpg"
      created_at="2017"
      description="Fernando miguel hernandez nava es el mejor de todo el mundo inclusive de toda la galaxia."
    />
    <card-component 
      title="Fernando"
      image="23.jpg"
      created_at="2017"
    />
    <card-component 
      title="Fernando"
      image="24.jpg"
      created_at="2017"
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
</style>