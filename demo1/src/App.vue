<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <test></test>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import test from './components/test.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    test
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
