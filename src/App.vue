<script setup>
import BaseNav from './components/BaseNav.vue';
</script>

<template>
  <header>
    <BaseNav />
  </header>
  <main>
    <RouterView />
  </main>
  <footer>

  </footer>
</template>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}
body {
  margin: 0;
}
main {
  padding: 0 1rem;
}
p {
    padding: 1rem;
    margin: 1rem;
    max-width: 20rem;
}
</style>