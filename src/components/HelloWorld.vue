<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <a href="https://twitter.com/_tommy_le3">Twitter</a>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
