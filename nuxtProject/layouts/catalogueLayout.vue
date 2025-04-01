<script setup lang="ts">
const navTxt = "Menu";
</script>

<template>
  <nav class="default-nav">
    <h2>{{ navTxt }}</h2>
  </nav>
  <slot></slot>
</template>

<style scoped>
.default-nav {
  background-color: aqua;
}
</style>
