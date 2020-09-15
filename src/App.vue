<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Hello World" name="Vinícius" age="20" tagMessage="Esse é um título"/>
    <Methods message="Essa é uma frase bem legal" reverseMessage="alert()"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Methods from './components/Methods.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Methods,
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
