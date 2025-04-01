<script setup lang="ts">
const bienvenida = "Bienvenido a catálogos";
const buttonTxt = "Ir a home";
definePageMeta({
  layout: "catalogue-layout",
});
</script>
<template>
  <h1>{{ bienvenida }}</h1>

  <NuxtLink to="/">
    <button class="to-home-button">{{ buttonTxt }}</button>
  </NuxtLink>
</template>
<style>
.to-home-button {
  background-color: rgb(245, 226, 164);
  border-radius: 2rem;
}
</style>
