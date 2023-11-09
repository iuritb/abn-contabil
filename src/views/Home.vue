<template>
  <div class="home">
    
    <NavBar />
    <CardSection />
  </div>
</template>

<script>
import CardSection from "../components/ui/card-section.vue";
import NavBar from "../components/ui/navbar.vue";
export default {
  components: {
    NavBar,
    CardSection,
  },
};
</script>

<style lang="scss" scoped>
</style>