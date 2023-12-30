<template>
  <section class="flex flex-col justify-center rotate-[-45deg] gap-0">
    <div class="flex">
      <SimonButton tag="Projects" />
      <SimonButton tag="About" />
    </div>
    <div class="flex">
      <SimonButton tag="Contact" />
      <SimonButton tag="Blog" />
    </div>
  </section>
</template>

<script setup>
import SimonButton from "./SimonButton.vue";
</script>

<style scoped></style>
