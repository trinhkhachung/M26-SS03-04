<template>
  <div>
    <h1>ex2ss4</h1>
    <h3>Company: {{user.name}}</h3>
    <h3>Age: {{user.age}}</h3>

    <button @click="handleClick">click</button>
  </div>

</template>

<script setup>
    import {reactive} from "vue"
    const user = reactive({
        name:"Rikkei Academy",
        age : 2,
    });
    const handleClick =()=>{
        user.name="Rikkei Education"
        user.age--;
    }
</script>

<style>

</style>