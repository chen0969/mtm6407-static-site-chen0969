<script setup>
import Header from '~/components/header.vue';
import DynaCard from '@/components/dynaCard.vue'; 
</script>

<template>
  <Header></Header>
  <div class="container">
    <div class="row">
      <h1 class="col-12">My Design Projects</h1>
    </div>
    <hr>
    <DynaCard title="Supply 0" tag1="Figma" tag2="Logo Design" tag3="Communication"
      description="The logo design and website layout redesign for Supply0 is an ongoing project that I am currently managing. As part of the design team, I collaborate remotely with my colleagues in Taiwan to develop and present various logo sketches, website prototypes, and numerous user interface designs to our client."
      imageUrl="_nuxt/media/supply0.png"></DynaCard>
    <hr>
  </div>
</template>

<style lang="scss"></style>
