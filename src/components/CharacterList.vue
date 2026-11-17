<script setup>
const characters = ["Leon", "Chris", "Ada", "Wesker", "Rebecca"]
</script>

<template>
  <section>
    <h2>Characters from RE</h2>
    <ul>
      <li v-for="character in characters">{{ character }}</li>
    </ul>
  </section>
</template>