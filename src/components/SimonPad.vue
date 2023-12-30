<template>
  <section class="flex flex-col justify-center rotate-[-45deg] gap-0">
    <div class="flex">
      <SimonButton tag="Projects" @click="$emit('navigate', '/projects')" />
      <SimonButton tag="About" @click="$emit('navigate', '/about')" />
    </div>
    <div class="flex">
      <SimonButton tag="Contact" @click="$emit('navigate', '/contact')" />
      <SimonButton
        tag="Blog"
        @click="
          console.log('%cThis will redirect to an external blog soon!', 'color:#66FF99')
        "
      />
    </div>
    <SimonCenterButton />
  </section>
</template>

<script setup>
import SimonButton from "./SimonButton.vue";
import SimonCenterButton from "./SimonCenterButton.vue";
</script>

<style scoped></style>
