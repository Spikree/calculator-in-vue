<template>
  <calculatorVue/>
</template>

<script>
import calculatorVue from './components/calculatorVue.vue'

export default {
  name: 'App',
  components: {
    calculatorVue
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
