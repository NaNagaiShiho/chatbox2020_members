<template>
  <section class="c-hero">
    <div class="c-hero__bg"></div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.c-hero {
  width: 100%;

  &__bg {
    min-height: 325px;
    background-image: url("~assets/image/member/hero/img_memberTop@2x.png");
    background-position: center;

    @include mobile {
      background-position: 28%;
    }
  }
}
</style>
