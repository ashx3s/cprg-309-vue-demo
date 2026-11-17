<script setup>
import { ref } from "vue"
// ref is used to make the variable "reactive". if it's an array or object, use reactive: https://vuejs.org/guide/essentials/reactivity-fundamentals.html

const title = "Declarative Rendering"
const count = ref(0)

</script>
<template>
  <section>
    <h2>{{ title.split(" ").reverse().join(" ") }}</h2>
    <p>Count is: {{ count }}</p>
  </section>
</template>