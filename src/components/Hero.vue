<script>
  export default {
    name: "Hero",
    components: {},
  };
</script>

<template>
  <div class="bg-black relative hidden py-5">
    <div class="bg-hero">
      <img
        src="../assets/img/bg-hero.svg"
        class="svg-hero"
        alt=""
        onload="SVGInject(this)"
      />
    </div>

    <section class="container flex-center hero">
      <div class="row">
        <div class="grid-7">
          <h6 class="h7 uppercase color-gradient line-hero">uma nova era</h6>
          <div class="">
            <h1 class="color-white">
              O banco <span class="icon1-hero">&nbsp;</span> pra chamar de
              <span class="icon2-hero">&nbsp;</span>
              <span class="color-gradient">seu</span>
            </h1>
          </div>

          <p class="mt-3" style="max-width: 520px">
            Lorem ipsum dolor sit amet consectetur. Et ut tempus facilisis
            tristique. Vitae consequat vel tortor aenean imperdiet posuere
            neque.
          </p>

          <a href="#" class="btn mt-4">Junte-se a nós</a>

          <div class="mt-4">
            <img
              src="../assets/img/fig10-paybank.png"
              class="icon-xxl"
              alt=""
              loading="lazy"
            />
          </div>
        </div>
        <div class="grid-5 relative div-card">
          <!--============ CARD VERSE ============-->
          <div class="card-fig card-verse card-transform-verse card-black">
            <div class="card-number p-2">
              <img
                src="../assets/img/icon-mastercard.svg"
                class="icon"
                alt=""
                onload="SVGInject(this)"
              />
              <h6 class="color-white h7 text-right mt-1">•••• 4859</h6>
            </div>
          </div>

          <!--============ CARD FRONT ============-->
          <div class="card-fig card-front card-transform-front">
            <div class="card-logo p-2">
              <img
                src="../assets/img/logo-card.svg"
                class="icon"
                alt=""
                onload="SVGInject(this)"
              />
            </div>
            <div class="card-contactless p-2">
              <img
                src="../assets/img/icon-contactless.svg"
                class="icon-s"
                alt=""
                onload="SVGInject(this)"
              />
            </div>

            <div class="card-content-description p-2">
              <h6 class="color-white h7">EDUARDO A GARCIA</h6>

              <img
                src="../assets/img/icon-mastercard.svg"
                class="icon mt-3"
                alt=""
                onload="SVGInject(this)"
              />
            </div>
          </div>

          <!--============ CARD ICONS ============-->
          <div class="bg-icon-white mr-1 icon-1-fig">
            <img
              src="../assets/img/icon-smartphone.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>

          <div class="bg-icon-white mr-1 icon-2-fig">
            <img
              src="../assets/img/icon-fingerprint.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>

          <div class="bg-icon-white mr-1 icon-3-fig">
            <img
              src="../assets/img/icon-shield.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped></style>
