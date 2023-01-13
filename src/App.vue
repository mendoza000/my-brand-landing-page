<script setup lang="ts">
import Header from "@/components/Header.vue";
import Navbar from "@/components/Navbar.vue";
import About from "@/components/About.vue";
import Support from "@/components/Support.vue";
import Benefits from "@/components/Benefits.vue";
import Prices from "@/components/Prices.vue";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <Navbar />
  <Header />
  <About />
  <Support />
  <Benefits />
  <Prices />
  <Footer />
</template>

<style>
/* width */
::-webkit-scrollbar {
  width: 8px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #f1f1f1;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #888;
  border-radius: 10px;
}
</style>
