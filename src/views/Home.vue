<template>
  <div class="home">
    <NavBar />
    <CardSection />
    <AboutUs />
    <ServiceSection />
  </div>
</template>

<script>
import ServiceSection from "../components/ui/service-section.vue"
import CardSection from "../components/ui/card-section.vue";
import AboutUs from "../components/ui/about-us.vue";
import NavBar from "../components/ui/navbar.vue";

export default {
  components: {
    NavBar,
    AboutUs,
    CardSection,
    ServiceSection
  },
};
</script>

<style lang="scss" scoped>
</style>