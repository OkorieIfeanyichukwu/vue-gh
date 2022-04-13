<template>
  <navigationA/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to my first vue App github repo"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import navigationA from './components/navigationA.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    navigationA,

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
