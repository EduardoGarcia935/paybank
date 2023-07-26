<script>
  export default {
    name: "TenhaControle",
    components: {},
  };
</script>

<template>
  <section class="container" id="section-1">
    <div class="row">
      <div class="grid-5">
        <h6 class="uppercase color-gradient h7">controle total</h6>
        <h3 class="mt-1">Todo o controle financeiro em um só lugar</h3>
        <p class="mt-3">
          Veja como você pode cuidar das suas finanças pelo app Paybank de forma
          segura, rápida e o melhor, no corforto da sua casa.
        </p>

        <!--============ CARD VERSE ============-->
        <div class="relative" style="min-height: 420px">
          <div
            class="card-fig card-verse card-transform-verse-2 card-black mt-5"
          >
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
          <div class="card-fig card-front card-transform-front-2">
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
      </div>
      <div class="grid-1"></div>
      <div class="grid-3">
        <div>
          <div class="bg-icon">
            <img
              src="../assets/img/icon-account.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="mt-2">
            <h6>Acompanhe sua conta</h6>
            <p class="mt-1">
              Acompanhar sua conta, fazer transferências e pagamentos de onde
              estiver.
            </p>
          </div>
        </div>

        <div class="mt-5">
          <div class="bg-icon">
            <img
              src="../assets/img/icon-bar.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="mt-2">
            <h6>Investimentos</h6>
            <p class="mt-1">
              Diversas opções de investimentos, de acordo com o seu perfil de
              investidor.
            </p>
          </div>
        </div>

        <div class="mt-5">
          <div class="bg-icon">
            <img
              src="../assets/img/icon-swap.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="mt-2">
            <h6>Câmbio</h6>
            <p class="mt-1">
              Diversas opções de investimentos, de acordo com o seu perfil de
              investidor.
            </p>
          </div>
        </div>
      </div>

      <div class="grid-3">
        <div>
          <div class="bg-icon">
            <img
              src="../assets/img/icon-no-tax.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="mt-2">
            <h6>Sem taxas</h6>
            <p class="mt-1">
              Acompanhar sua conta, fazer transferências e pagamentos de onde
              estiver.
            </p>
          </div>
        </div>

        <div class="mt-5">
          <div class="bg-icon">
            <img
              src="../assets/img/icon-card-virtual.svg"
              class="icon"
              alt=""
              onload="SVGInject(this)"
            />
          </div>
          <div class="mt-2">
            <h6>Cartão virtual</h6>
            <p class="mt-1">
              Acompanhe a fatura do seu cartão de crédito e faça compras online
              com seu cartão virtual.
            </p>
          </div>
        </div>

        <a href="#" class="btn-freq mt-6 ml-3">Perguntas <br />Frequentes</a>
      </div>
    </div>
  </section>
</template>
