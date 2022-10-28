<script setup>
import Landing from './landing.vue'
import Footing from './components/footer.vue'
// TODO : Use Vue Router
</script>

<template>
  <Landing/>
  <Footing/>
</template>

<style>
@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 100 900;
  font-display: swap;
  src: url('https://rsms.me/inter/font-files/Inter-roman.var.woff2') format('woff2');
  font-named-instance: 'Regular';
}
:root {
  font-family: 'Inter', sans-serif;
}
body {
  margin: 0;
}
</style>
