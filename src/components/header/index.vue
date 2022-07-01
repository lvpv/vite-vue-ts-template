<template>
  <h1>Hello</h1>
  <h2>{{ count }}</h2>
  <button @click="increment">+1</button>
</template>

<script lang="ts" setup name="Header">
  import { ref } from 'vue'
  const count = ref(0)
  const increment = () => count.value++
</script>

<style scoped></style>
