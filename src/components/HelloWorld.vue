<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <h2>{{ msg }}</h2>

  <div class="card">
    <h3 class="text-4xl font-bold text-gray-800">We're Coming Soon 🚀</h3>
    <p class="mt-4 text-lg text-gray-600"> The future of AI is almost here. Stay tuned.</p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
