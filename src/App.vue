<script setup>
import { RouterLink, RouterView } from "vue-router";
import Header from "./components/Header.vue";
import Sidebar from "./components/Sidebar.vue";
</script>

<template>
  <Header />
  <main class="main">
    <Sidebar />
    <RouterView />
  </main>
</template>
