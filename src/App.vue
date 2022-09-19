<script setup>
import { RouterLink, RouterView } from "vue-router";
import Header from "./components/Header.vue";
import Sidebar from "./components/Sidebar.vue";
</script>

<template>
  <main class="main">
    <Header />
    <Sidebar />
    <main class="main__body">
      <RouterView />
    </main>
  </main>
</template>
