<script setup>
import { ref } from 'vue'
  const counter = ref(0);
  function increase() {
    counter.value++;
    console.log(counter.value)
  }
</script>

<template>
  <button @click="increase">Count is: {{ counter }}</button>
  <button @click="counter=0">Reset</button>
</template>

<style scoped>

</style>
