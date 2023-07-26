<script>
  export default {
    name: "ScreenLoader",
    components: {},
  };
</script>

<template>
  <div class="screen-loading flex-column">
    <div class="logo-paybank">
      <div class="logo-part-1"></div>
      <div class="logo-part-2"></div>
    </div>
    <div class="bar-loader mt-1"></div>

    <img
      src="../assets/img/bg-hero.svg"
      class="svg-screen-loading"
      alt=""
      onload="SVGInject(this)"
    />
  </div>
</template>

<style scoped></style>
