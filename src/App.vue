<template>
  <header>
    <div class="wrapper">
      <nav>
        <Navbar />
        <!-- <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/projects">Projects</RouterLink> -->
      </nav>
    </div>
  </header>
</template>

<script setup>
import { RouterLink, RouterView } from "vue-router";
import Navbar from "./components/Navbar.vue";
</script>

<style></style>
