<!--
 * @Author: Admin 12564610+sea-cyber_0@user.noreply.gitee.com
 * @Date: 2023-03-18 21:56:34
 * @LastEditors: Admin 12564610+sea-cyber_0@user.noreply.gitee.com
 * @LastEditTime: 2023-03-18 23:08:53
 * @FilePath: \nodejs\vue项目\test2\src\App.vue
 * @Description: 
 * 
 * Copyright (c) 2023 by ${git_name_email}, All Rights Reserved. 
-->
<template>
  <div id="app">
   <div class="hell"><HelloWorld msg="Welcome to Your Vue.js App"/></div>
    <h1>nihk</h1>
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
