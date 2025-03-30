<script setup>
import Header from '~/components/header.vue';
import DynaCard from '@/components/dynaCard.vue'; 
</script>

<template>
  <Header></Header>
  <div class="container">
    <div class="row">
      <h1 class="col-12">My Web-Dev Projects</h1>
    </div>
    <hr>
    <DynaCard title="JFY & CapitalE" tag1="Catalogue" tag2="Portrait" tag3="Graphic"
      description="As a photographer for JFY Disposable Tableware and Capital E Bag, my role involves producing over 1,000 commercial photographs for these start-up retailers, assisting them in creating a catalog for client review and marketing purposes. Notably, my work with JFY marks the beginning of my career and has evolved into a long-term partnership. I continue to contribute to the company remotely as a social media manager, enhancing its online presence and engagement."
      imageUrl="_nuxt/media/jfy-capitale.png"></DynaCard>
    <hr>
  </div>
</template>

<style lang="scss"></style>
