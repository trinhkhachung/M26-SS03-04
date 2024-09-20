<template>
  <div>
    <h2>Ex5ss04</h2>
    <h3>mèn mén loại 1 - số lượng : {{num.one}}</h3>
    <button @click="handleClick">tăng số lượng</button>
    <h3>mèn mén loại 2 - số lượng : {{num.tow}}</h3>
    <button @click="handleTow">tăng số lượng</button>
    <h3>mèn mén loại 3 - số lượng : {{num.three}}</h3>
    <button @click="handleThree">tăng số lượng</button>
    <h3>tổng số lượng:{{num.one+num.tow+num.three}}</h3>
    
  </div>
</template>

<script setup>
    import {reactive} from "vue"
    const num = reactive({
        one:10,
        tow:20,
        three:3,
    });
    function handleClick (){
        return num.one +=1
    };
    function handleTow (){
        return num.tow +=1
    };
    function handleThree (){
        return num.three +=1
    };

</script>

<style>

</style>