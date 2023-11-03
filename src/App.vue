<template>
  <div id="app">
    <AppHeader />
    <AppHero />
    <AppCards />
    <AppCarousel />
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
import AppHero from "@/components/AppHero.vue";
import AppCards from "@/components/AppCards.vue";
import AppCarousel from "@/components/AppCarousel.vue";
export default {
  components: {
    AppHeader,
    AppHero,
    AppCards,
    AppCarousel,

  },
};
</script>

<style>
</style>
