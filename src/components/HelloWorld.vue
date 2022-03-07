<template>
  <div class="hello">
    <p>{{ msg }}</p>
  </div>
</template>

<script>


export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
  margin-top: 30px;
}
p {
  display: block;
  font-family: monospace;
  white-space: nowrap;
  border-right: 4px solid;
  width: 61ch;
  animation: typing 7s steps(61), blink 1s infinite step-end alternate;
  overflow: hidden;
  color: white;
  margin: auto;
  font-size: 25px;
  font-weight: 600
}

@keyframes typing {
  from { width: 0 }
}
@media (max-width: 600px) {
  .hello {
    word-wrap: break-word;
  }
}
</style>
