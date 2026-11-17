<script setup>
import { ref } from 'vue'

const awesome = ref(true)

const toggle = () => awesome.value = !awesome.value
</script>

<template>
  <section>

    <button @click="toggle">Toggle</button>
    <h2 v-if="awesome === true">Vue is awesome!</h2>
    <h2 v-else>Oh no 😢</h2>
  </section>
</template>