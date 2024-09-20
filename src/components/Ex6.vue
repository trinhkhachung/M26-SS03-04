<template>
  <div>
    <h1>Ex06</h1>
    <button @click="handleClick('Rikkei Academy')">Get param</button>
  </div>
</template>
    
    <script setup>
const handleClick = (message) => {
  console.log("da lay thong tin: ", message);
};
</script>
    
    <style>
</style>