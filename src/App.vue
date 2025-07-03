<script setup>
import { ref } from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import AppBar from './components/AppBar.vue'

const count = ref(0)
</script>

<template>
  <AppBar msg="First" />
  <h1>This is second</h1>
</template>

<style scoped>
.logo {
  height: 6em;
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
.read-the-docs {
  color: #888;
}
</style>
