<script setup lang="ts">
const navTxt = "Header";
const footerTxt = "Footer";
</script>

<template>
  <nav class="default-nav">
    <h2>{{ navTxt }}</h2>
  </nav>
  <slot></slot>
  <footer class="default-footer">
    <h2>{{ footerTxt }}</h2>
  </footer>
</template>

<style scoped>
.default-nav {
  background-color: rgb(123, 255, 255);
}
.default-footer {
  background-color: rgb(0, 255, 38);
}
</style>
