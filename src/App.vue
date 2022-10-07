<template>
  <div id="app">
    <myCalculator />
  </div>
</template>

<script>
import myCalculator from './components/my-calculator.vue'
export default {
  name: 'app',
  components: {
    myCalculator
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>