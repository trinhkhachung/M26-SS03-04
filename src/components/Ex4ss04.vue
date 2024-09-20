<template>
    <div>
        <h1>Ex04ss04</h1>
  <input type="text" v-model="data">
    </div>
</template>

<script setup>
    import{ref,watch} from "vue"
    const data = ref("")
    watch(data,(newValue, oldValue)=>{
        console.log(`giá trị thay đổi từ ${oldValue}thành${newValue}`);
        
    });
    
</script>

<style>

</style>