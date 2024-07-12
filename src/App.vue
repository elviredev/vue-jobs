<script setup>
import Navbar from "@/components/Navbar.vue";
import { RouterView } from "vue-router";
</script>

<template>
  <main class="selection:bg-green-500 selection:text-white">
    <Navbar />
    <RouterView />
  </main>
</template>


