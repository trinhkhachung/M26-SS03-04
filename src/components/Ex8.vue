<template>
  <div>
    <h1>Ex08</h1>
    <a @click.stop.prevent="doThat" href="http://www.google.com"
      >404 khong tim thay trang</a
    >

    <a href=" https://www.google.com">da truy cap duong dan</a>
  </div>
</template>
    
    <script setup>
const doThat = () => {
  alert("Duong dan khong ton tai");
};
</script>
    
    <style>
</style>