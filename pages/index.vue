<script setup>
import Header from '~/components/header.vue';
import Card from '~/components/card.vue';

const cards = [ 
  { title: 'Design', tagline: 'My Design Projects', link: '/design' },
  { title: 'Develop', tagline: 'My Web-Development Projects', link: '/develop' },
  { title: 'Photo', tagline: 'My Photography Projects', link: '/photo' }];
</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <Header></Header>
    <div class="container">
      <div class="row m-5">
        <h1 class="col-12 text-center">Jing-An's Snap Protfolio!</h1>
        <h2 class="col-12 text-center m-3">
          Let's see what I did in this 2 years.
        </h2>
      </div>
      <div class="row justify-content-center">
        <Card v-for="(card, index) in cards" :key="index" :title="card.title" :tagline="card.tagline"
          :link="card.link" />
      </div>
    </div>
  </div>
</template>

<style lang="scss">
</style>
