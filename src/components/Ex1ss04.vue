<template>
  <div>
    <h1>
        Count:{{count}}
    </h1>
    <button @click="countClick">click 1 lần</button>
    <button @dblclick="countClick">click 2 lần</button>
  </div>
</template>

<script setup>
    import {ref} from 'vue'
    const count = ref(0)
    const randomNumber = ref(1)
    const countClick =()=>{
        count.value++;
    }
</script>

<style>

</style>