<script setup lang="ts">
import ThemeToggle from "./components/ThemeToggle.vue";
import { RouterView } from "vue-router";
</script>

<template>
  <ThemeToggle class="theme-toggler"/>
  <RouterView />
</template>

<style lang="scss">
@import '@/styles/App.scss';
html {
  transition: 1s;
  background-color: $bg-color-light;
  color: $text-color-light;
  font-family: 'Sora', sans-serif;
}

.dark {
  background-color: $bg-color-dark;
  color: $text-color-dark;
}

.theme-toggler {
  display: flex;
  justify-content: flex-end;
  margin: 1rem;
}
</style>
