<script setup>
import ComponentProps from './ComponentProps.vue';
const cards = [
  { id: 1, cardTitle: "title 1", cardDescription: "1 2 3 4" },
  { id: 2, cardTitle: "title 2", cardDescription: "5 6 7 9" }
]
</script>
<template>
  <section>
    <ComponentProps v-for="card in cards" :id="card.id" :card-title="card.cardTitle"
      :card-description="card.cardDescription" />
  </section>
</template>
<style scoped>
section {
  display: flex;
  gap: 12px;
  margin: 20px auto;
}
</style>