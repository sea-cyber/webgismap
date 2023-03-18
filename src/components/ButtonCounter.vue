<template>
    <button @click="count++" class="">
      You clicked me {{ count }} times.
    </button>
  </template>
<script>
export default {
    name:'ButtonCounter',
    data(){
        return{
            count:0
        }
    }
}
</script>
<style>
button
   { width: 100px;
    height: 100px;}

</style>
