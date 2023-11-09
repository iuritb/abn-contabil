<template>
  <div class="services">
    <div class="services__title">Nossos Serviços</div>
    <div>
      <v-row justify="center" class="services__collapse">
        <v-expansion-panels accordion>
          <v-expansion-panel v-for="(item, i) in 3" :key="i">
            <v-expansion-panel-header>Item</v-expansion-panel-header>
            <v-expansion-panel-content>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </v-expansion-panel-content>
          </v-expansion-panel>
        </v-expansion-panels>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.services {
  margin: 124px 0 50px 0;
  &__title {
    color: #333;
    font-size: 48px;
    font-style: normal;
    font-weight: 700;
    line-height: 52.8px; /* 110% */
    text-align: center;
  }
  &__collapse{
    margin: 24px 160px;
  }
}
</style>