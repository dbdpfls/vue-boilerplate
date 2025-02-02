<script setup lang="ts">
import StoreTest from '@/components/StoreTest.vue'
</script>

<template>
  <div class="about">
    <StoreTest />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
