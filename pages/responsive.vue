<template>
  <div>
    .columns.is-mobile
    <div class="columns is-mobile is-gapless">
      <div class="column is-half">.column.is-half</div>
      <div class="column">2</div>
      <div class="column">3</div>
      <div class="column">4</div>
    </div>
    .columns.is-desktop
    <div class="columns is-desktop">
      <div class="column">1</div>
      <div class="column">2</div>
      <div class="column">3</div>
      <div class="column">4</div>
    </div>
    .columns.is-vcentered
    <div class="columns is-vcentered">
      <div class="column is-8">
        <p>.column.is-8</p>
      </div>
      <div class="column">
        <p>Second column with more content. This is so you can see the vertical alignmen.Second column with more content. This is so you can see the vertical alignmen.Second column with more content. This is so you can see the vertical alignmen.Second column with more content. This is so you can see the vertical alignmen.Second column with more content. This is so you can see the vertical alignmen.Second column with more content. This is so you can see the vertical alignmen.</p>
      </div>
    </div>
  </div>
</template>
<style scoped>
  .column {
    background-color: rgba(188, 178, 191, 0.44);
    border-radius: 40px;
  }

</style>
