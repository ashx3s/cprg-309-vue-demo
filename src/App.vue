<script setup>
import AttributeBind from './components/AttributeBind.vue';
import CharacterList from './components/CharacterList.vue';
import ConditionalRender from './components/ConditionalRender.vue';
import DeclarativeRender from './components/DeclarativeRender.vue';
import EventListener from './components/EventListener.vue';
import FormBinding from './components/FormBinding.vue';
import ListRender from './components/ListRender.vue';
const title = "VueJS Tutorial"


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
    <ListRender />
  </main>
</template>

<style scoped></style>
