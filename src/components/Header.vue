<script setup>
import SupportIcon from "./icons/SearchIcon.vue";
import FileIcon from "./icons/FileIcon.vue";
import BallIcon from "./icons/BallIcon.vue";
import MassageIcon from "./icons/MassageIcon.vue";
</script>
<template>
  <header class="header">
    <h1 class="header__title">Dashboard</h1>
    <div class="header__link-wrapper">
      <SupportIcon class="header__link-icon" />
      <FileIcon class="header__link-icon" />
      <BallIcon class="header__link-icon" />
      <MassageIcon class="header__link-icon" />
      <img class="header__image" src="/profile-logo.png" alt="logo" />
    </div>
  </header>
</template>
