<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="" target="">
      <img src="./assets/logo.png" class="logo vue" alt="logo" />
    </a>
  </div>
  <HelloWorld msg="AI at the Core. Excellence at the Edge" />
</template>

<style scoped>
.logo {
  height: 25em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
