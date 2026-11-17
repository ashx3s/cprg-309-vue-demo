<script setup>
const characters = ["Leon", "Chris", "Ada", "Wesker", "Rebecca"]
</script>

<template>
  <ul>
    <li v-for="character in characters">{{ character }}</li>
  </ul>
</template>