<template>
  <div id="app">
    <search></search>
  </div>

</template>

<script>
import Search from './components/Search.vue'

export default {
  name: 'App',
  components: {
    Search
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin:-10%;
  background-color:black;
}
</style>
