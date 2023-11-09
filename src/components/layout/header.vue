<template>
  <v-card padless class="header">
    <v-container>
      <v-row>
        <v-col>
          <img
            class="mt-10 ml-6 header__logo"
            width="100%"
            src="../../assets/img/logo-banner.svg"
            alt="Placeholder image"
          />
          <div class="mt-14 header__text">
            <h1 class="header__title">
              Seu Sucesso, Nossa Estratégia Tributária.
            </h1>
            <p class="mt-6 header__description">
              Maximize seus ganhos e minimize seus impostos com nossa expertise
              contábil.
            </p>
          </div>
        </v-col>
        <v-col>
          <div class="header__navigation">
            <p class="header__navigation-text">Sobre nós</p>
            <p class="header__navigation-text">Nossos Serviços</p>
            <p class="header__navigation-text">E-book</p>
            <v-btn class="header__navigation-button" color="#D6C7B4"
              >Fale conosco</v-btn
            >
          </div>
          <!-- <div class="group">
            <div class="group__background"></div>
            <div class="group__front"></div>
          </div> -->
        </v-col>
      </v-row>
    </v-container>
  </v-card>
</template>

<script>
// import batata from "../../assets/img/"
export default {};
</script>

<style lang="scss" scoped>
.header {
  background-color: rgba(31, 51, 75, 1);
  flex-shrink: 0;
  width: 100%;
  height: 659px;
  &__logo {
    display: flex;
    width: 367px;
    height: 114px;
    flex-shrink: 0;
  }
  &__text {
    margin-left: 96px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    gap: 51px;
    width: 607px;
    height: 231px;
    box-sizing: border-box;
    font-family: Inter;
    color: #fff;
    text-align: left;
  }
  &__title {
    line-height: 61.6px;
    font-weight: 700;
    font-size: 56px;
    width: 607px;
    height: 97px;
  }
  &__description {
    line-height: 28px;
    font-weight: 400;
    font-size: 20px;
    width: 596px;
    height: 83px;
  }
  &__navigation {
    display: flex;
    flex-direction: row;
    justify-content: end;
    align-items: center;
    flex-shrink: 0;
  }
  &__navigation-text {
    margin: 29px 14px;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 25.2px;
    color: #fff;
  }
  &__navigation-button {
    border-radius: 8px;
    font-size: 16px;
    font-style: normal;
    font-weight: 700;
    line-height: 22.4px; /* 140% */
    color: #fff;
  }
}

.group {
  &__background {
    background-image: url(../../assets/img/group.svg);
  }
  &__front {
    background-image: url(../../assets/img/image-banner.png);
  }
}
</style>