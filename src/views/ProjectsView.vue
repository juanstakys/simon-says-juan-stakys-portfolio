<template>
  <div>
    <ul>
      <li v-for="index in 10" :key="index">
        <p>{{ index }}</p>
      </li>
    </ul>
  </div>
</template>

<script setup></script>

<style scoped></style>
