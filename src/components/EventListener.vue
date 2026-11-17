<script setup>
import { ref } from 'vue'

const count = ref(0)
const increment = () => count.value++
const decrement = () => count.value--
</script>

<template>
  <!-- make this button work -->
  <h2>Count is: {{ count }}</h2>
  <button @click="increment">Increment</button>
  <button @click="decrement">Decrement</button>
</template>