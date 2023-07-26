<script>
  export default {
    name: "FooterVue",
    components: {},
  };
</script>

<template>
  <footer class="mt-4">
    <div class="row bb-gray">
      <div class="grid-4 flex-start-row">
        <img
          src="../assets/img/logo-paybank.svg"
          class="icon"
          alt=""
          onload="SVGInject(this)"
        />
        <h6 class="ml-1">Paybank.</h6>
      </div>
      <div class="grid-4">
        <h5>Be the first to hearour sight banking news</h5>
      </div>
      <div class="grid-4 flex-start-row">
        <input type="text" placeholder="Digite aqui o seu e-mail" />
        <button class="btn-send flex-center ml-2">
          <img
            src="../assets/img/icon-send.svg"
            class="icon-s"
            alt=""
            onload="SVGInject(this)"
          />
        </button>
      </div>
    </div>
    <div class="row">
      <div class="grid-3">
        <h5>Stay connect with anyone & anywhere</h5>
      </div>
      <div class="grid-5 flex-center mt-3">
        <a href="#" class="mx-1 bg-social-networks">
          <img
            src="../assets/img/icon-facebook.svg"
            class="icon w-auto"
            alt=""
            onload="SVGInject(this)"
          />
        </a>
        <a href="#" class="mx-1 bg-social-networks">
          <img
            src="../assets/img/icon-instagram.svg"
            class="icon w-auto"
            alt=""
            onload="SVGInject(this)"
          />
        </a>
        <a href="#" class="mx-1 bg-social-networks">
          <img
            src="../assets/img/icon-twitter.svg"
            class="icon w-auto"
            alt=""
            onload="SVGInject(this)"
          />
        </a>
        <a href="#" class="mx-1 bg-social-networks">
          <img
            src="../assets/img/icon-youtube.svg"
            class="icon w-auto"
            alt=""
            onload="SVGInject(this)"
          />
        </a>
      </div>
      <div class="grid-4">
        <div class="flex-start-row mt-1">
          <a href="#" class="btn-white flex-start-row">
            <img
              src="../assets/img/icon-apple.svg"
              class="icon fill-svg-green"
              alt=""
              onload="SVGInject(this)"
            />
            <h6 class="h7 ml-1">Apple&nbsp;Pay</h6>
          </a>
          <a href="#" class="btn-white flex-start-row ml-2">
            <img
              src="../assets/img/icon-googleplay.svg"
              class="icon fill-svg-green"
              alt=""
              onload="SVGInject(this)"
            />
            <h6 class="h7 ml-1">Google&nbsp;Pay</h6>
          </a>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="grid-3 py-0">
        <p class="text-center">© 2022 PayBank.com</p>
      </div>
      <div class="grid-3 py-0 disappear"></div>
      <div class="grid-3 py-0 disappear"></div>
      <div class="grid-3 py-0 flex-center">
        <p class="text-center">Powered by Násser Yousef:</p>
        <a href="http://nasseryousef.com.br/" class="ml-1" target="_blank">
          <img
            src="../assets/img/icon-ny.svg"
            class="icon"
            alt=""
            onload="SVGInject(this)"
          />
        </a>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
