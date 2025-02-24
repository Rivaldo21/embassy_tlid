<script setup>
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import News from "./components/News.vue";
import VisiMisi from "./components/VisiMisi.vue";
import Faq from "./components/Faq.vue";
import QuickLink from "./components/QuickLink.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <Header />
  <Banner />
  <News />
  <VisiMisi />
  <Faq />
  <QuickLink />
  <Footer />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&display=swap");

body {
  font-family: "Manrope", serif;
  max-width: 1728px;
  margin: auto;
}
</style>
