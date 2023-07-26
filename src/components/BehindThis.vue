<script>
  export default {
    name: "BehindThis",
    components: {},
  };
</script>

<template>
  <section class="container" id="section-4">
    <div class="row">
      <div class="grid-6">
        <div class="people-paybank p-3">
          <img src="../assets/img/img1-paybank.png" alt="" />
        </div>
      </div>
      <div class="grid-6">
        <h6 class="uppercase color-gradient h7">pessoas reais</h6>
        <h3 class="mt-1">
          Por trás disso tudo, tem um objetivo:
          <span class="color-gradient">pessoas</span>
        </h3>
        <p class="mt-3">
          Lorem ipsum dolor sit amet consectetur. Et ut tempus facilisis
          tristique. Vitae consequat vel tortor aenean imperdiet posuere neque.
          Sollicitudin at at volutpat scelerisque ut aliquet velit tempor.
        </p>
      </div>
    </div>
    <div class="row">
      <div class="grid-6">
        <div class="people-paybank p-3">
          <img src="../assets/img/img2-paybank.png" alt="" />
        </div>

        <a
          href="#"
          class="btn-white flex-start-row mt-4"
          style="display: inline-block"
        >
          <div class="flex-start-row">
            <img
              src="../assets/img/icon-instagram.svg"
              class="icon fill-svg-green"
              alt=""
              onload="SVGInject(this)"
            />
            <h6 class="h7 mx-1">Instagram</h6>
            <img
              src="../assets/img/icon-arrow-up.svg"
              class="icon fill-svg-green"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
        </a>

        <h4 class="mt-3">
          Por isso, nos siga no <br />
          Instagram
        </h4>
      </div>
      <div class="grid-6">
        <div class="people-paybank p-2">
          <img src="../assets/img/img3-paybank.png" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
