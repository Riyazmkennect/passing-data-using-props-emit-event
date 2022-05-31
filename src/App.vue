<template>
  <div id="app">
    <HelloWorld msg="Passing data"/>
    <Paren/>
    <Child name="alishaa"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Paren from './components/Paren .vue'
import Child from './components/ Child.vue'
import Paren from './components/Paren.vue'
import Child from './components/Child.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Paren,
    Child,
    Paren,
    Child
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
