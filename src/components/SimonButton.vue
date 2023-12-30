<template>
  <div class="flex border h-32 w-32 justify-center items-center">
    <h2 class="rotate-45">{{ props.tag }}</h2>
  </div>
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps(["tag"]);
</script>

<style scoped></style>
