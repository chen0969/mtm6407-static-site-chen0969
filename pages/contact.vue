<script setup>
import Header from '~/components/header.vue';
import SocialBtn from '~/components/socialBtn.vue';
</script>

<template>
    <Header></Header>
    <div class="container">
      <div class="row"><h1 class="col-12 text-center">Contact Me</h1></div>
      <div class="row mt-5 justify-content-center">
        <SocialBtn title="Facebook" link="https://www.facebook.com/BroccoliDesigner" icon="bi-facebook" />
        <SocialBtn title="Iinkedin" link="https://www.linkedin.com/in/broccolidesign/" icon="bi-linkedin" />
        <SocialBtn title="Instagram" link="https://www.instagram.com/huyohiya/" icon="bi-instagram" />
      </div>
    </div>
</template>
