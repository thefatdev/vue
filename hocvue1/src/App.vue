<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <hearderComponent />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <cakeNew msg="xin chao cac anh em "/>
    <footerComponent /> 
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import cakeNew from './components/cakeNew.vue'
import hearderComponent from './components/headerComponent.vue'
import footerComponent from './components/footerComponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    cakeNew,
    hearderComponent,
    footerComponent
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
