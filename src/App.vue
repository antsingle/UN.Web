<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HotTable msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HotTable from './components/HotTable.vue'

export default {
  name: 'app',
  components: {
    HotTable
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
