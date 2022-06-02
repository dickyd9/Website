<script setup>
import { RouterLink, RouterView } from "vue-router";
import HeaderVue from "./components/header/Header.vue";
import Footer from "./components/footer/Footer.vue";
</script>

<template>
  <div class="outer-wrapper">
    <HeaderVue />
     <RouterView />
    <Footer />
  </div>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}

@media (min-width: 1024px) {
  body {
    display: flex;
    place-items: center;
  }

  .outer-wrapper {
    position: relative;
    min-width: 1024px;
  }

  #app {
    padding: 0 2rem;
  }

  main {
      padding-top: 5rem;
      position: relative;
  }

  .main-wrapper {
    display: inline;
    margin-top: 2rem;

  }
}
</style>