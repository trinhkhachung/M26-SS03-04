<template>
    <div>
        <h1>Ex3</h1>
        <input type="text" :disabled="isDisabled">
    <input type="text" v-bind:disable="isDisabled">
    </div>
    

</template>

<script setup>
    const isDisabled = true;
</script>

<style>

</style>