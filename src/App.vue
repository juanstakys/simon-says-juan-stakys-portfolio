<template>
  <nav>
    <router-link to="/" class="hover:underline hover:italic">Home</router-link>
  </nav>
  <section class="text-center">
    <router-view @navigate="(link) => this.$router.push(link)" />
  </section>
</template>

<style></style>
