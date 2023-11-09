<template>
  <div class="image-card-image-card" style="props.style">
    <div class="image-card-shadow" />
    <div class="image-card-background">
      <div class="image-card-box_5101303951013038x">
        <p class="image-card-otimizao-fiscal">{{ title }}</p>
        <p class="image-card-body">
          {{ description }}
        </p>
      </div>
    </div>
    <img :src="loadAsset(image)" />
  </div>
</template>

<script>
// import batata from "../../assets/img/"
export default {
  name: "ImageCard",
  props: {
    title: {
      type: String,
      default: "none",
    },
    description: {
      type: String,
      default: "none",
    },
    image: {
      type: String,
      default: "none",
    },
  },

  methods: {
    loadAsset(path) {
      return require(`../../assets/img/${path}`);
    },
  },
};
</script>

<style lang="scss" scoped>
.image-card-image-card {
  text-align: left;
  justify-content: center;
  display: flex;
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  position: relative;
  padding-bottom: 203px;
  box-sizing: border-box;
  height: 500px;
  width: 352px;
}

.image-card-shadow {
  border-radius: 8px;
  bottom: 23px;
  right: 12px;
  background-color: rgba(189, 189, 189, 0.8);
  filter: blur(36px);
  position: absolute;
  box-sizing: border-box;
  height: 236px;
  width: 321px;
}

.image-card-background {
  border-radius: 8px;
  margin-right: auto;
  margin-left: auto;
  bottom: 0;
  right: 0;
  justify-content: center;
  display: flex;
  background-color: rgba(255, 255, 255, 1);
  left: 0;
  position: absolute;
  padding-right: 26px;
  padding-left: 26px;
  padding-bottom: 52px;
  padding-top: 24pxpx;
  box-sizing: border-box;
  height: 260px;
  width: 352px;
}

.image-card-box_5101303951013038x {
  width: 100%;
  height: 100%;
  justify-content: space-around;
  flex-direction: column;
  display: flex;
  gap: 8px;
  box-sizing: border-box;
}

.image-card-otimizao-fiscal {
  color: #092C4C;
  width: 208px;
  height: 27px;
  line-height: 26.4px;
  font-weight: 700;
  font-size: 24px;
}

.image-card-body {
  color: rgba(79, 79, 79, 1);
  line-height: 22.4px;
  font-weight: 400;
  font-size: 16px;
  width: 300px;
  height: 92px;
}

.image-card-image {
  // background: url("../../assets/img/image-2.jpeg") center / cover rgba(196, 196, 196, 1);
  border-top-right-radius: 8px;
  border-top-left-radius: 8px;
  background-color: rgba(196, 196, 196, 1);
  box-sizing: border-box;
  height: 297px;
  width: 352px;
}
</style>