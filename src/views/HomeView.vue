<template>
  <div class="flex justify-center mt-32">
    <SimonPad @navigate="(link) => $emit('navigate', link)" />
  </div>
</template>

<script setup>
import SimonPad from "@/components/SimonPad.vue";
</script>
