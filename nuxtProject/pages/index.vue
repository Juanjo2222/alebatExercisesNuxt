<script setup lang="ts">
const bienvenida = "Bienvenido a la home";
const buttonTxt = "Ir a catálogos";
</script>
<template>
  <h1>{{ bienvenida }}</h1>
  <NuxtLink to="/catalogue">
    <button class="to-catalogue-button">{{ buttonTxt }}</button>
  </NuxtLink>
</template>
<style>
.to-catalogue-button {
  background-color: rgb(245, 226, 164);
  border-radius: 2rem;
}
</style>
