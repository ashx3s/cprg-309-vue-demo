<script setup>
import AttributeBinding from './components/AttributeBinding.vue';
import CharacterList from './components/CharacterList.vue';
import DeclarativeRender from './components/DeclarativeRender.vue';

const title = "Resident Evil Characters"


</script>

<template>
  <main>
    <h1>{{ title }}</h1>
    <CharacterList />
    <DeclarativeRender />
    <AttributeBinding />
  </main>
</template>

<style scoped></style>
