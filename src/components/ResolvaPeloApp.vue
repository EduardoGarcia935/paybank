<script>
  export default {
    name: "ResolvaPeloApp",
    components: {},
  };
</script>

<template>
  <section class="container" id="section-2">
    <div class="row">
      <div class="grid-5">
        <h6 class="uppercase color-gradient h7">FEITO PENSANDO EM VOCÊ</h6>
        <h2 class="mt-1">
          Resolva tudo pelo <span class="color-gradient py-1">App</span>
        </h2>
        <p class="mt-3">
          Lorem ipsum dolor sit amet consectetur. Et ut tempus facilisis
          tristique. Vitae consequat vel tortor aenean imperdiet posuere neque.
          Sollicitudin at at volutpat scelerisque ut aliquet velit tempor.
        </p>

        <div class="flex-start-row mt-4 mb-2">
          <div class="bg-icon">
            <img
              src="../assets/img/icon-chart.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="ml-2">
            <h6>Controle total sobre seus gastos</h6>
            <p class="p4 mt-1">Tudo na palma da sua mão</p>
          </div>
        </div>

        <div class="flex-start-row mt-4 mb-2">
          <div class="bg-icon">
            <img
              src="../assets/img/icon-investment.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="ml-2">
            <h6>Acesso a uma carteira de investimentos</h6>
            <p class="p4 mt-1">Tudo na palma da sua mão</p>
          </div>
        </div>
      </div>
      <div class="grid-1 disappear"></div>
      <div class="grid-6">
        <img
          src="../assets/img/fig4-paybank.png"
          class=""
          alt=""
          onload="SVGInject(this)"
        />
      </div>
    </div>
  </section>
</template>

<style scoped></style>
