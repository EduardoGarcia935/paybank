<script>
  export default {
    name: "AllYouNeed",
    components: {},
  };
</script>

<template>
  <div class="bg-black-light relative hidden">
    <div class="bg-cta">
      <img src="../assets/img/bg-hero.svg" alt="" onload="SVGInject(this)" />
    </div>

    <section class="container" id="section-8">
      <div class="row text-cta">
        <div class="grid-2"></div>
        <div class="grid-8 flex-center flex-column">
          <h6 class="uppercase color-gradient text-center">paybank</h6>
          <h2 class="mt-1 color-white text-center">
            Tudo que você precisa em um só lugar
          </h2>
          <p class="mt-3 text-center">
            We plant a tree for everyone who pre-registers and every new
            customer. And we're planning to plant millions.
          </p>

          <a href="#" class="btn mt-4">Junte-se a nós</a>
        </div>
        <div class="grid-2"></div>
      </div>
    </section>
  </div>
</template>
