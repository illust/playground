<template>
  <div id="app">
    <Netflix msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Netflix from './components/Netflix.vue'

export default {
  name: 'App',
  components: {
    Netflix
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
body {
    margin: 0;
    padding: 0;
  }
</style>
