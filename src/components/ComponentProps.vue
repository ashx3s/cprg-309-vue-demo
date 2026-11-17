<script setup>
const props = defineProps({
  cardTitle: String,
  cardDescription: String,
})
</script>
<template>
  <article>
    <h3>{{ cardTitle || "Card Title" }}</h3>
    <p>{{ cardDescription || "Placeholder Description" }}</p>
  </article>
</template>

<style scoped>
article {
  background-color: thistle;
  width: 10rem;
  padding: 20px;
  border-radius: 20px;
}
</style>