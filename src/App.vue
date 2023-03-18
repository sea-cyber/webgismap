<template>
  <div id="app">
   <div class="hell"><HelloWorld msg="Welcome to Your Vue.js App"/></div>
    
    <div class="button"><ButtonCounter/></div> 
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ButtonCounter from './components/ButtonCounter.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    ButtonCounter
  }
}
</script>

<style>
#app {
  width: 400px;
  height: 300px;
  border: 1px solid black;
  margin: auto;
}
.hell,.button{
  width: 400px;
  height: 150px;
  border: 1px  solid red;
  margin: auto;
}
</style>
