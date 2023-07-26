<script>
  export default {
    name: "CardPaybank",
    components: {},
  };
</script>

<template>
  <section class="container" id="section-7">
    <div class="row">
      <div class="grid-6 relative div-card">
        <div class="card-fig card-verse card-black card-1-scrub">
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

        <div class="card-fig card-front card-2-scrub">
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
            <h6 class="color-white h7">NASSER Y S ALI</h6>

            <img
              src="../assets/img/icon-mastercard.svg"
              class="icon mt-3"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
        </div>
      </div>
      <div class="grid-6">
        <h6 class="uppercase color-gradient">um cartão pra chamar de seu</h6>
        <h2 class="mt-1">Minimalista. Simples. Eficiente.</h2>
        <p class="mt-3">
          Revid Card features an RFID transponder in its core that enables you
          to pay with a touch-free wave.
        </p>

        <div class="flex-start-row mt-4 mb-4">
          <div class="bg-icon">
            <img
              src="../assets/img/icon-vip.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="ml-2">
            <h6>Acesso a salas VIP</h6>
            <p>An obligation in which a third party agrees to repay a debt.</p>
          </div>
        </div>

        <div class="flex-start-row mt-2 mb-4">
          <div class="bg-icon">
            <img
              src="../assets/img/icon-card-virtual.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="ml-2">
            <h6>Cartão virtual</h6>
            <p>An obligation in which a third party agrees to repay a debt.</p>
          </div>
        </div>

        <div class="flex-start-row mt-2 mb-4">
          <div class="bg-icon">
            <img
              src="../assets/img/icon-download.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="ml-2">
            <h6>Create a deposit</h6>
            <p>An obligation in which a third party agrees to repay a debt.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
