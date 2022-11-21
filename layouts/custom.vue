<template>
  <NuxtLink to="/about">
    <div class="center">Custom layout</div>
  </NuxtLink>
</template>

<script setup lang="ts">
  const layout = "custom";
</script>

<style scoped>
  .center {
    margin: auto;
    width: 50%;
    border: 3px solid darkred;
    padding: 10px;
    text-align: center;
  }
</style>
