<template>
  <div class="header container">
    <span class="header__title">Where in the world?</span>
    <button>dark/light</button>
  </div>
</template>

<script>
export default {
  name: "HeaderNavigation",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/assets/scss/mixins.scss";
.header {
  height: 80%;
  @include flex(row, space-between, center);
  &__title {
    @include font(24px, 600);
  }
}
</style>
