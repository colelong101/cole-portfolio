<script setup></script>

<template>
  <div class="home-container">
    <header class="hero-section bg-black">
      <div class="radial-glow"></div>
      <div class="overlay"></div>
      <div class="container">
        <h1 class="name-text">
          <span class="fw-bold">Cole Long</span>
        </h1>
        <h1>
          <span class="text-primary fw-semi">Dev</span> |<span
            class="text-white fw-semi"
          >
            UI/UX</span
          >
        </h1>
        <p class="lead pt-2">
          with a focus on creating minimalistic web interfaces and beautiful
          user experiences
        </p>
        <h5>Technologies:</h5>
        <div class="icon-row">
          <i class="fab fa-php"></i>
          <i class="fab fa-js"></i>
          <i class="fab fa-vuejs"></i>
          <i class="fab fa-laravel"></i>
          <i class="fab fa-sass"></i>
          <i class="fab fa-python"></i>
        </div>
      </div>
    </header>

    <section class="py-5 bg-black">
      <div class="container">
        <div class="row">
          <div class="col-md-7">
            <div class="about-me">
              <h2 class="fw-bold text-white about-me-title">About Me</h2>
              <p class="about-text pt-3 text-white">
                Passionate frontend web developer with a background in Cloud
                Computing and Cloud App Development from WSU Tech. 1 year of
                professional experience in Vue, Laravel, MySQL, and SCSS,
                complemented by proficiency in Figma for prototyping.
                Enthusiastic about all things tech. I enjoy quality time with
                family and golf during leisure.
              </p>
            </div>
            <div class="pt-3">
              <h5 class="fw-bold text-white">
                See My Work
                <span class="text-primary">
                  <router-link class="" to="/projects">Here</router-link>
                </span>
                <i class="fas fa-rocket" style="margin-left: 12px"></i>
                <!-- You can adjust the value of margin-left as needed -->
              </h5>
            </div>
          </div>
          <div class="col-md-5">
            <img
              style="border-radius: 20px"
              src="../assets/cole-long-portrait.jpg"
              alt="Cole Long Portrait"
            />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style>
@import "../assets/main.css";
</style>
