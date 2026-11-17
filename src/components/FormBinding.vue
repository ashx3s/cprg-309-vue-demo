<script setup>
import { ref } from 'vue'
// v-model makes 2 way binding easy. instead of needing to create a function to update on keystroke you just use v-model to connect the variable to the form element that updates it.
const text = ref('')

</script>

<template>
  <section>
    <h2>Form Input Binding</h2>
    <input v-model="text" placeholder="Type here">
    <p>Text Input: {{ text }}</p>
  </section>
</template>