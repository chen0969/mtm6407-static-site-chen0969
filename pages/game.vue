<script setup>
import Header from '~/components/header.vue';
</script>

<template>
  <Header></Header>
  <div class="container">
    <div class="row">
        <h1 class="col-12 text-center">Let's Play</h1>
        <h5 class="col-12 text-center">Fun fact, I have a gamification web-portfolio, please feel free to play with it!</h5>
    </div>
    <hr>
    <div class="embed-container">
    <iframe
    class="rounded"
      src="https://canada-broccoli.github.io/canadabroccoli/"
      width="100%"
      height="600"
      frameborder="0"
      title="My game"
    ></iframe>
  </div>
    <hr>
  </div>
</template>

<style lang="scss">
.embed-container {
  width: 100%;
  height: 600px;
  overflow: hidden;
}

iframe {
  width: 100%;
  height: 100%;
  border: none;
}
</style>
