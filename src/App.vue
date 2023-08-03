<template>
  <div id="app">
    <h3>Capatcha generator</h3>
    <Capatcha />
  </div>
</template>

<script>
import Capatcha from './components/Capatcha.vue'

export default {
  name: 'App',
  components: {
    Capatcha
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
  margin-top: 60px;
}
</style>
