<template>
  <div>
    <p class="question">
      Would you be my {{whatever}}
    </p>
    <button @click="showConfetti" class="button">Yes</button>
  </div>
</template>

<script>
import JSConfetti from 'js-confetti'

const jsConfetti = new JSConfetti()


export default {
  name: 'WouldYou',
  props:{
    whatever: {
      type: String,
      default: 'GF'
    }
  },
  methods: {
    showConfetti() {
      jsConfetti.addConfetti()
    }
  }
}
</script>

<style lang="css" scoped>
.question {
  color: crimson;
}
.button {
  background: pink;
  
}
</style>
