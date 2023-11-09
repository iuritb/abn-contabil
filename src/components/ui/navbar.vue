<template>
  <div class="navbar">
    <div class="navbar__text">
      <div class="navbar__text-item">Receita Federal</div>
      <div class="navbar__text-item">Meu INSS</div>
      <div class="navbar__text-item">ISS Online</div>
      <div class="navbar__text-item">ISS Net Online</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
p {
  margin: 0;
}
.navbar {
  background-color: #e0e0e0;
  box-sizing: border-box;
  height: 96px;
  width: 100%;
  &__text {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
  }
  &__text-item {
    margin-top: 35px;
    color: #4f4f4f;
    font-size: 18px;
    font-style: normal;
    font-weight: 700;
    line-height: 25.2px; /* 140% */
  }
}
</style>