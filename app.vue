<script setup lang="ts">
const greeting = ref('Hello world')
</script>

<template lang="pug">
h1 {{ greeting }}
</template>

<style>
html,
body,
#__nuxt {
  height: 100vh;
  margin: 0;
  padding: 0;
}

html.dark {
  background: #222;
  color: white;
}
</style>
