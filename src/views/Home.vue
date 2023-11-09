<template>
  <div class="home">
    <NavBar />
    <CardSection />
    <AboutUs />
    <ServiceSection />
    <EBook /> 
  </div>
</template>

<script>
import ServiceSection from "../components/ui/service-section.vue"
import CardSection from "../components/ui/card-section.vue";
import AboutUs from "../components/ui/about-us.vue";
import NavBar from "../components/ui/navbar.vue";
import EBook from "../components/ui/ebook.vue"

export default {
  components: {
    EBook,
    NavBar,
    AboutUs,
    CardSection,
    ServiceSection
  },
};
</script>

<style lang="scss" scoped>
</style>