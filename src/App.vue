<script setup>
import HelloWorld from './components/HelloWorld.vue'
import cabeza from './components/header.vue'
import contenido1 from './components/inicio.vue'
import piedepagina from './components/footer.vue'
</script>

<template>
  <cabeza  />
  <contenido1  />
  <piedepagina  />
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
</style>
