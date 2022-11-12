<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <SPA msg="Welcome to Your Vue.js App"/>
</template>

<script>
import SPA from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    SPA
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
