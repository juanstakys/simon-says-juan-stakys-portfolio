<template>
  <div class="flex flex-col items-center">
    <p>These are my contact links! Here you go!</p>
    <div class="flex flex-row gap-10">
      <div v-for="i in 3" :key="i">
        <a href="#" class="hover:underline">link {{ i }}</a>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
