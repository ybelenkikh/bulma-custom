<template>
  <header class="">
    <p class="has-text-centered">
    .container.is-fluid.has-text-centered // 32px
    </p>
    <div class="container is-flex is-flex-wrap-wrap is-justify-content-center">
      <nuxt-link to="/button"><button class="button is-large is-success">button</button></nuxt-link>
      <nuxt-link to="/spacing"><button class="button is-large is-success">spacing <br /> margin\padding </button></nuxt-link>
      <nuxt-link to="/typography"><button class="button is-large is-success"> typography </button></nuxt-link>
      <nuxt-link to="/columns"><button class="button is-large is-success"> Columns </button></nuxt-link>
      <nuxt-link to="/layout"><button class="button is-large is-success">layout</button></nuxt-link>
      <nuxt-link to="/flexbox"><button class="button is-large is-success">flexbox</button></nuxt-link>
      <nuxt-link to="/tiles"><button class="button is-large is-success">tiles</button></nuxt-link>
      <nuxt-link to="/form"><button class="button is-large is-success">form</button></nuxt-link>
      <nuxt-link to="/Responsiveness"><button class="button is-large is-success">Responsiveness</button></nuxt-link>
    </div>
  </header>
</template>
<style scoped>
  button{
    margin-bottom: 1em;
    margin-right: 1em;
  }
</style>
