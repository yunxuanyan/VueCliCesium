<template>
  <div id="app">
    <CesiumMap></CesiumMap>
  </div>
</template>

<script>
import CesiumMap from './components/CesiumMap.vue';

export default {
  name: 'app',
  components: {
    CesiumMap
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
