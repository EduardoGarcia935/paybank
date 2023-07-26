<script>
  export default {
    name: "Investimentos",
    components: {},
  };
</script>

<template>
  <section class="container" id="section-6">
    <div class="row">
      <div class="grid-6">
        <h6 class="uppercase color-gradient">investimentos</h6>
        <h3 class="mt-1">
          Mais dinheiro na sua <span class="color-gradient py-1">carteira</span>
        </h3>

        <div>
          <h6 class="color-gray mt-4">
            Para começar, qual o valor você gostaria de investir
          </h6>
          <div class="flex-space">
            <h5 class="mt-1 bold">
              R$ <span class="money-investment">1000</span>
            </h5>
            <div class="flex-start-row">
              <div class="button-minus flex-center button-minus-money">
                <img
                  src="../assets/img/icon-minus.svg"
                  class="icon"
                  alt=""
                  onload="SVGInject(this)"
                />
              </div>
              <div class="button-plus flex-center ml-3 button-plus-money">
                <img
                  src="../assets/img/icon-plus.svg"
                  class="icon"
                  alt=""
                  onload="SVGInject(this)"
                />
              </div>
            </div>
          </div>
        </div>

        <div>
          <h6 class="color-gray mt-3">
            Quanto tempo deixaria seu dinheiro investido?
          </h6>
          <div class="flex-space">
            <h5 class="mt-1 bold">
              <span class="time-investment">12</span> meses
            </h5>
            <div class="flex-start-row">
              <div class="button-minus flex-center button-minus-time">
                <img
                  src="../assets/img/icon-minus.svg"
                  class="icon"
                  alt=""
                  onload="SVGInject(this)"
                />
              </div>
              <div class="button-plus flex-center ml-3 button-plus-time">
                <img
                  src="../assets/img/icon-plus.svg"
                  class="icon"
                  alt=""
                  onload="SVGInject(this)"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="grid-1 disappear"></div>
      <div class="grid-5">
        <p class="mt-1">
          Aqui na Paybank, você investe com ao menos
          <b>100% do CDI (13.75%&nbsp;a.a.)</b>
          automaticamente, aqui seu dinheiro rende bem mais que a poupança.
          Coloque os valores e veja você mesmo.
        </p>

        <div class="bt-gray mt-4">
          <h6 class="color-gray mt-4">na sua carteira terá</h6>
          <h2 class="color-gradient my-2">
            R$ <span class="result-investment">60845.54</span>
          </h2>
          <h6 class="color-gray">em 1 ano rendendo na PayBank</h6>
        </div>

        <p class="text-center p5 mt-6" style="max-width: 580px">
          Valores utilizados no simulador de investimentos (referentes à data de
          última atualização - esses valores podem alterar de acordo com o
          mercado): <br />
          Data da última atualização: 03/03/23
        </p>
      </div>
    </div>
  </section>
</template>
