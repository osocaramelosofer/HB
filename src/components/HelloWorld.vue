<template>
  <div class="hello">
    
    <span>{{ msg }}</span>
    <would-you whatever="Friend"/>
  </div>
</template>

<script>
import WouldYou from './WouldYou.vue'

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    WouldYou,
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
span {
  display: block;
  font-family: monospace;
  white-space: nowrap;
  border-right: 4px solid;
  width: 61ch;
  animation: typing 7s steps(61), blink 1s infinite step-end alternate;
  overflow: hidden;
  color: white;
  margin: auto;
}

@keyframes typing {
  from { width: 0 }
}
</style>
