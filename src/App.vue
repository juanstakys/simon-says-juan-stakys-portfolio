<template>
  <nav>
    <router-link to="/" class="hover:underline hover:italic flex flex-col items-center">
      <img src="./assets/portrait.png" alt="Protrait" class="h-40 w-36 mt-4" />
      <div
        class="text-center text-transparent bg-clip-text bg-gradient-to-r from-black to-blue-400"
      >
        <h1 class="text-7xl">Juan Cruz Stakys</h1>
        <h2 class="text-4xl">- Frontend developer -</h2>
      </div>
    </router-link>
  </nav>
  <section class="mt-12">
    <router-view @navigate="(link) => this.$router.push(link)" />
  </section>
</template>

<style></style>
