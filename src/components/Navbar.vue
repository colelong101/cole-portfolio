<template>
  <div>
    <nav class="p-3 navbar navbar-expand-lg sticky-top bg-black">
      <div class="container">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="justify-content-end collapse navbar-collapse"
          id="navbarNav"
        >
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <RouterLink class="nav-link text-light" to="/">Home</RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink class="nav-link text-light" to="/projects"
                >Projects</RouterLink
              >
            </li>
            <li class="nav-item">
              <RouterLink class="nav-link text-light" to="/contact-me"
                >Contact Me</RouterLink
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link text-light"
                href="https://github.com/colelong101"
                target="blank"
                ><i class="fab fa-github"></i
              ></a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link text-light"
                href="https://www.linkedin.com/in/cole-long-633813239?trk=people-guest_people_search-card"
                target="blank"
                ><i class="fab fa-linkedin"></i
              ></a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light" href="../pdf/resume.pdf" download
                ><i class="fas fa-download"></i
              ></a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
  <RouterView />
</template>

<style>
.content-container {
  height: 100vh;
  overflow-y: auto; /* Enable scrolling if the content overflows */
}
</style>

<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>
