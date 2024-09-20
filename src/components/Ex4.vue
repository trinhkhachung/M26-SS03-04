<template>
  <div>
    <h1>Ex04</h1>
    <div :class="{ active: isActive }" :style="{ backgroundColor: bgColor }">
      <p>Block</p>
    </div>
  </div>
</template>
  
  <script setup>
const isActive = true;

const bgColor = "blue";
</script>
  
  <style scoped>
.active {
  color: #f5f5f5;
}
</style>