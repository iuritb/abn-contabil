<template>
  <div class="home">
    <NavBar />
    <CardSection />
    <AboutUs />
  </div>
</template>

<script>
import CardSection from "../components/ui/card-section.vue";
import AboutUs from "../components/ui/about-us.vue";
import NavBar from "../components/ui/navbar.vue";

export default {
  components: {
    NavBar,
    AboutUs,
    CardSection,
  },
};
</script>

<style lang="scss" scoped>
</style>