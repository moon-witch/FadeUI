<script setup lang="ts">
import MainButton from "@/components/MainButton.vue";
</script>

<template>
  <div class="fadewrap">
    <div class="fade-ui">FadeUI</div>
    <div>
      <MainButton content="fade in" />
    </div>
  </div>
</template>

<style scoped lang="scss">
.fadewrap {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 85vh;
  padding: 0;
  margin: 0;
}
.fade-ui {
  font-size: 5rem;
  font-weight: 100;
  user-select: none;
}
</style>
