<template>
  <div class="container">
    <div class="">
      <div class="columns">
        <div class="column">
          <div class="block block-a pl-1">
            .block
          </div>

        </div>
        <div class="column">
          <div class="box block-a">
            .box
          </div>
        </div>
      </div>
      <div>
        <p>nav.breadcrumb.is-right</p>
        <p class="ml-2">ul>li>a</p>
        <nav class="breadcrumb is-right" aria-label="breadcrumbs">
          <ul>
            <li><a href="#">Bulma</a></li>
            <li><a href="#">Documentation</a></li>
            <li><a href="#">Components</a></li>
            <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
          </ul>
        </nav>
      </div>
      <div>
        <p>nav.breadcrumb.is-right.has-arrow-separator</p>
        <p class="ml-2">ul>li>a</p>
        <nav class="breadcrumb is-right has-arrow-separator" aria-label="breadcrumbs">
          <ul>
            <li><a href="#">Bulma</a></li>
            <li><a href="#">Documentation</a></li>
            <li><a href="#">Components</a></li>
            <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
          </ul>
        </nav>
      </div>
      <div>
        <p>nav.breadcrumb.is-right.has-bullet-separator.is-large</p>
        <p class="ml-2">ul>li>a</p>
        <nav class="breadcrumb is-right has-bullet-separator is-large" aria-label="breadcrumbs">
          <ul>
            <li><a href="#">Bulma</a></li>
            <li><a href="#">Documentation</a></li>
            <li><a href="#">Components</a></li>
            <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
          </ul>
        </nav>
      </div>
      <div>
        <p>nav.breadcrumb.is-right.has-dot-separator.is-medium</p>
        <p class="ml-2">ul>li>a</p>
        <nav class="breadcrumb is-right has-dot-separator is-medium" aria-label="breadcrumbs">
          <ul>
            <li><a href="#">Bulma</a></li>
            <li><a href="#">Documentation</a></li>
            <li><a href="#">Components</a></li>
            <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
          </ul>
        </nav>
      </div>
      <div>
        <p>nav.breadcrumb.is-right.has-succeeds-separator.is-small</p>
        <p class="ml-2">ul>li>a</p>
        <nav class="breadcrumb is-right has-succeeds-separator is-small" aria-label="breadcrumbs">
          <ul>
            <li><a href="#">Bulma</a></li>
            <li><a href="#">Documentation</a></li>
            <li><a href="#">Components</a></li>
            <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
          </ul>
        </nav>
      </div>
      <div>

      </div>
    </div>
    <p>.card</p>
    <p class="ml-2">|.card-image</p>
    <p class="ml-4">figure.image</p>
    <p class="ml-5">img</p>
    <p class="ml-2">|.card-content</p>
    <p class="ml-4">p.title</p>
    <p class="ml-4">p.subtitle</p>
    <p class="ml-2">|.card-footer</p>
    <p class="ml-4">.card-footer-item</p>
    <p class="ml-4">.card-footer-item</p>

    <div class="card block-b">
      <div class="card-image">
        <figure class="image">
          <img src="" alt="image">
        </figure>
      </div>
      <div class="card-content">
        <p class="title">
          “There are two hard things in computer science: cache invalidation, naming things, and off-by-one errors.”
        </p>
        <p class="subtitle">
          Jeff Atwood
        </p>
      </div>
      <footer class="card-footer">
        <a href="#" class="card-footer-item">Save</a>
        <a href="#" class="card-footer-item">Edit</a>
        <a href="#" class="card-footer-item">Delete</a>
      </footer>
    </div>
  </div>
</template>
<style scoped>
  .block-a {
    color: #ffffff;
    background-color: #cb6363;
  }

  .block-b {
    background-color: #9fc463;
  }

</style>
