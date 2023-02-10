<script setup>
import Navbar from "./components/Home/Nav/Navbar.vue";
import Logo from "./components/Home/Logo/Logo.vue";
import Footer from "./layout/Footer/Footer.vue"


</script>

<template>
  <div class="container max-w-auto mx-auto">
    <Navbar />
    <Logo />
    <Footer />
  </div>
</template>

<style scoped>
.container {
  background-color: #2D2E32;
}
</style>
