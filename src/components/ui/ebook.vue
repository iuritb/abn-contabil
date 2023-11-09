<template>
  <div class="ebook-banner">
    <div class="ebook-banner__text">
      <p class="ebook-banner__text-title">
        E-book sobre Planejamento Tributário
      </p>
      <p class="ebook-banner__text-description">
        Lorem ipsum dolor sit amet, consectetur <br />
        adipiscing elit, sed do eiusmod tempor incididunt
      </p>
      <v-btn class="download-button" color="#D6C7B4"> Baixar agora </v-btn>
    </div>
    <div class="ebook-banner__image"></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.ebook-banner {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin: 120px 220px;
  border-radius: 8px;
  background: #092c4c;
  height: 232px;
  flex-shrink: 0;
  &__text {
    margin-top: 42px;
  }
  &__text-title {
    color: var(--Color---White, #fff);
    font-size: 32px;
    font-style: normal;
    font-weight: 700;
    line-height: 35.2px; /* 110% */
  }
  &__text-description {
    color: #fff;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 22.4px; /* 140% */
  }
  &__image {
    display: flex;
    align-self: flex-end;
    background-image: url(../../assets/img/image-4.png);
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
    box-sizing: border-box;
    height: 210px;
    width: 255px;
  }
}
.download-button {
  color: #fff;
  width: 163px;
  height: 55px !important;
  border-radius: 8px;
  font-size: 14px;
  font-style: normal;
  font-weight: 700;
  line-height: 28px; /* 140% */
  gap: 10px;
}
</style>