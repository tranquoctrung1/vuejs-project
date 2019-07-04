<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <abc hello="Trần Quốc Trung"></abc>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import abc from './components/abc.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    abc
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
