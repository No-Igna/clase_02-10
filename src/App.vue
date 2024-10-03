<script setup>
import Saludo from './components/Saludo.vue'
import Usuario from './components/Usuario.vue'
import Contador from './components/Contador.vue'
</script>

<template>
  <Saludo/>
  <Usuario/>
  <Contador/>
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
