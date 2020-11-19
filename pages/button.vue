<template>
  <div>
    <div class="rows">
      <button class="row button">button.button</button>
      <button class="row button is-primary is-small">button.button.is-primary.is-small</button>
      <button class="row button is-link is-medium">button.button.is-link.is-medium</button>
      <button class="row button is-info is-large">button.button.is-info.is-large</button>
      <button class="row button is-success">button.button.is-success</button>
      <button class="row button is-warning">button.button.is-warning</button>
      <button class="row button is-danger">button.button.is-danger</button>
      <button class="row button is-danger is-outlined">button.button.is-danger.is-outlined</button>
      <p>//button.button.is-loading</p>
      <button class="row button is-loading">button.button.is-loading</button>
      <button class="row button" disabled>button.button disabled</button>
    </div>
  </div>
</template>
<style scoped>
  .rows{
    display: flex;
    flex-direction: column;
  }
</style>
