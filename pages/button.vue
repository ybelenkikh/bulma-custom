<template>
  <div>
    <p class="has-text-centered">.container //margin: 0 auto, width: auto, flex-grow: 1</p>
    <p class="has-text-centered">.has-text-centered</p>
    <div class="rows container ">
      <button class="row button block">button.button.block</button>
      <button class="row button is-primary is-small block">button.button.is-primary.is-small.block</button>
      <button class="row button is-link is-medium box">button.button.is-link.is-medium.box</button>
      <button class="row button is-info is-large box">button.button.is-info.is-large.box</button>
      <button class="row button is-success is-rounded">button.button.is-success.is-rounded</button>
      <button class="row button is-warning">button.button.is-warning</button>
      <button class="row button is-danger">button.button.is-danger</button>
      <button class="row button is-danger is-outlined">button.button.is-danger.is-outlined</button>
      <p class="has-text-centered">button.button.is-loading</p>
      <button class="row button is-loading">button.button.is-loading</button>
      <button class="row button" disabled>button.button disabled</button>
      <p>a.delete.is-large</p>
      <a href="" class="delete is-large"></a>
      <p>figure.image.is-128x128</p>
      <p class="ml-2">img</p>
      <figure class="image is-128x128">
        <img src="https://bulma.io/images/placeholders/128x128.png">
      </figure>
      <span class="icon is-left">
        <font-awesome-icon :icon="['fas', 'envelope']"/>
      </span>
    </div>
  </div>
</template>
<style scoped>
  .rows {
    display: flex;
    flex-direction: column;
  }

</style>
