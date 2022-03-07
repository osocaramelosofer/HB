<template>
  <div id="app" class="container">
    <HelloWorld msg="Happy Birthday to the most cute  n' funny girl in my life 💙."/>
    <mosaico-component />
    <footer-component />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MosaicoComponent from './components/MosaicoComponent.vue'
import FooterComponent from './components/footerComponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MosaicoComponent,
    FooterComponent
  },
  data(){
    return {}
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html {
  /* Set a Perfect Full Page Background Image */
  background: url('./assets/wallpaper.jpg') no-repeat center center fixed;
  background-size: cover;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding: 0;

}

</style>
