<template>
  <div class="flex flex-col items-center">
    <ul>
      <li v-for="index in 10" :key="index">
        <p>Project {{ index }}</p>
      </li>
    </ul>
  </div>
</template>

<script setup></script>

<style scoped></style>
