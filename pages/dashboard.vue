<template>
  <Heading>Dashboard</Heading>
  <div>Add your dashboard idea here</div>
  <p class="pb-4">Add your content here: {{ counter }}</p>
  <UButton @click="increment">Increment</UButton>
</template>

<script setup lang="ts">
const counter = ref(0);

const increment = () => {
  counter.value++;
};
</script>
