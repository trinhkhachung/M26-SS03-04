<template>
  <div>
    <h3>khi width = {{num.width}}</h3>
    <h3>khi height = {{num.height}}</h3>
    <h3>acreage:{{num.width*num.height}}</h3>
    <button @click="handleClick">click</button>
  </div>
</template>

<script setup>
    import {reactive} from "vue"
    const num = reactive({
        width:10,
        height:20,
        
    });
    function handleClick (){
        return num.width +=10
    };
</script>

<style>

</style>