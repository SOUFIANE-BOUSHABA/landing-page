<template>
  <div id="app">
    <AppHeader />
    <AppHero />
    <AppCards />
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
import AppHero from "@/components/AppHero.vue";
import AppCards from "@/components/AppCards.vue";
export default {
  components: {
    AppHeader,
    AppHero,
    AppCards,

  },
};
</script>

<style>
</style>
