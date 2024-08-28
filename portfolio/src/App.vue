<template>
  <div class="min-h-screen border-blue-900 bg-gradient-to-b from-cyan-500 to-blue-500 border-2 rounded-3xl font-serif max-w-7xl mx-auto py-5">
    <Header />
    <div class="mt-12">
      <RouterView />
    </div>
    <Footer />
  </div>
</template>

<script setup>
import { RouterView } from "vue-router";
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
</script>

<style scoped></style>