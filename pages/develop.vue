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
    <DynaCard title="Yizixue LMS" tag1="Laravel" tag2="Front-End" tag3="Web Design"
      description="Yizixue is an initiative focused on developing a learning management system (LMS). Previously, this project faced challenges that resulted in stagnation within the development cycle. To address these issues, we implemented a new communication framework designed to enhance collaboration among the front-end, back-end, and client teams."
      imageUrl="_nuxt/media/yizixue.png"></DynaCard>
    <hr>
  </div>
</template>

<style lang="scss"></style>
