<template>
  <div id="app">
    <Hero />
    <Titolone />
  </div>
</template>

<script>
import Titolone from './components/Titolone.vue'
import Hero from './components/Hero.vue'


export default {
  name: 'App',
  components: {
    Titolone,
    Hero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
