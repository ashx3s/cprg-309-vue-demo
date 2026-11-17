<script setup>
import AttributeBind from './components/AttributeBind.vue';
import CharacterList from './components/CharacterList.vue';
import ConditionalRender from './components/ConditionalRender.vue';
import DeclarativeRender from './components/DeclarativeRender.vue';
import EventListener from './components/EventListener.vue';
import FormBinding from './components/FormBinding.vue';

const title = "Resident Evil Characters"


</script>

<template>
  <main>
    <h1>{{ title }}</h1>
    <CharacterList />
    <DeclarativeRender />
    <AttributeBind />
    <EventListener />
    <FormBinding />
    <ConditionalRender />
  </main>
</template>

<style scoped></style>
