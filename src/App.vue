<template>
  <div id="app">
    <WelcomeToPortFolio/>
  </div>
</template>

<script>
import WelcomeToPortFolio from './components/WelcomeToPortFolio.vue'

export default {
  name: 'App',
  components: {
    WelcomeToPortFolio
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
