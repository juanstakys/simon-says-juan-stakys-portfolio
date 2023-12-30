<template>
  <section class="flex flex-col justify-center rotate-[-45deg] gap-0">
    <div class="flex">
      <SimonButton tag="Projects" @click="handleClick('/projects')" />
      <SimonButton tag="About" @click="handleClick('/about')" />
    </div>
    <div class="flex">
      <SimonButton tag="Contact" @click="handleClick('/contact')" />
      <SimonButton
        tag="Blog"
        @click="
          console.log('%cThis will redirect to an external blog soon!', 'color:#66FF99')
        "
      />
    </div>
    <!-- Center Button should start the Simon Game -->
    <SimonCenterButton />
  </section>
</template>

<script setup>
import { defineEmits } from "vue";

import SimonButton from "./SimonButton.vue";
import SimonCenterButton from "./SimonCenterButton.vue";

const emit = defineEmits(["navigate"]);

function handleClick(link) {
  // TO-DO: Make simon playable
  emit("navigate", link);
}
</script>

<style scoped></style>
