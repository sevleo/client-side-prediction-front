<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="about flex flex-col">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/game">Play</RouterLink>
    <p>This is About view</p>
  </div>
</template>
