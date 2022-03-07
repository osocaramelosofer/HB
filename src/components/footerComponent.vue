<template>
  <div class="hello">
    <p>
        "No conoces a una persona en un par de dias o semanas, ni siquiera meses.
        Y para ser honesto no estoy seguro si algun dia terminas de concoer a alguien, 
        porque apesar de que lleves anos conociendo a alguien, cada dia hay detalles en su persona
        que antes no sabias, ni siquiera ella misma. Pero desde que crei haber conocido a Iridian nunca mas me dieron ganas
        de alejarme de ella" (Fernando, 2021).
    </p>
  </div>
</template>

<script>


export default {
  name: 'FooterComponent',
  props: {

  },
  components: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: yellow;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.hello {

    width: 1000px;
    overflow-wrap: break-word;
    /* word-break: break-all; */
    margin: auto;
    margin-bottom: 50px;
    background: white;
    border-radius: 10px;
    padding-block: 50px;
    padding-inline: 50px;
}
p {
  font-family: monospace;
    
  color: black;
  margin: auto;
  font-size: 25px;
  line-height: 25px;


}

</style>
