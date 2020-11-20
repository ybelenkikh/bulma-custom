<template>
  <div class="container">
    <p>.container</p>
    <p class="ml-2">.level</p>
    <p class="ml-4">.level-left</p>
    <p class="ml-6">.level-item</p>
    <p class="ml-6">.level-item</p>
    <p class="ml-4">.level-right</p>
    <p class="ml-6">.level-item</p>
    <p class="ml-6">.level-item</p>
    <p class="ml-6">.level-item</p>
    <p class="ml-6">.level-item</p>
    <p class="ml-6">.level-item</p>
    <nav class="level mb-6">

      <div class="level-left">
        <div class="level-item">
          <p class="subtitle is-5">
            <strong>123</strong> posts
          </p>
        </div>
        <div class="level-item">
          <div class="field has-addons">
            <p class="control">
              <input class="input" type="text" placeholder="Find a post">
            </p>
            <p class="control">
              <button class="button">
                Search
              </button>
            </p>
          </div>
        </div>
      </div>

      <!-- Right side -->
      <div class="level-right">
        <p class="level-item"><strong>All</strong></p>
        <p class="level-item"><a>Published</a></p>
        <p class="level-item"><a>Drafts</a></p>
        <p class="level-item"><a>Deleted</a></p>
        <p class="level-item"><a class="button is-success">New</a></p>
      </div>
    </nav>
    <hr>
    <hr>
    <hr>
    <p>|.media</p>
    <p class="ml-2">|figure.media-left</p>
    <p class="ml-4">|p.image.is-64x64</p>
    <p class="ml-5">|img</p>
    <p class="ml-2">|.media-content</p>
    <p class="ml-4">|.content</p>
    <p class="ml-5">|p</p>
    <p class="ml-6">|strong small</p>
    <p class="ml-2">|.media-right</p>
    <p class="ml-4">|button.delete</p>
    <article class="media">
      <figure class="media-left">
        <p class="image is-64x64">
          <img src="https://bulma.io/images/placeholders/128x128.png">
        </p>
      </figure>
      <div class="media-content">
        <div class="content">
          <p>
            <strong>John Smith</strong> <small>@johnsmith</small> <small>31m</small>
            <br>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ornare magna eros, eu pellentesque tortor vestibulum ut. Maecenas non massa sem. Etiam finibus odio quis feugiat facilisis.
          </p>
        </div>
      </div>
      <div class="media-right">
        <button class="delete"></button>
      </div>
    </article>
  </div>
</template>
<style scoped>

</style>
