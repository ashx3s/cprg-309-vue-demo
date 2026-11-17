<script setup>
import { ref } from 'vue'
// A directive is a special attribute that starts with the v- prefix. They are part of Vue's template syntax

const titleClass = ref('title')
</script>
<template>
  <section>
    <!-- Use attribute binding anytime you need to use js to update an attribute. -->
    <h2 :class="titleClass">Attribute Binding</h2>
    <p></p>
  </section>
</template>
<style scoped>
.title {
  color: red;
}
</style>