<template>
  <div id="app">
    <Crossword msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Crossword from './components/Crossword.vue'

export default {
  name: 'App',
  components: {
    Crossword
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
