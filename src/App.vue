<script setup>
import CharacterList from './components/CharacterList.vue';
import DeclarativeRender from './components/DeclarativeRender.vue';

const title = "Resident Evil Characters"


</script>

<template>
  <main>
    <h1>{{ title }}</h1>
    <CharacterList />
    <DeclarativeRender />
  </main>
</template>

<style scoped></style>
