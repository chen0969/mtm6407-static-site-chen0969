<script setup>
defineProps({
  title: String,
  tag1: String,
  tag2: String,
  tag3: String,
  description: String,
  imageUrl: String
});
</script>

<template>
  <div class="row g-3">
    <!-- Title section -->
    <h2 class="col-md-6">{{ title }}</h2>

    <!-- Links section, which might change dynamically -->
    <div class="col-md-2 p-2">
      <span class="text-center p-2">
        {{ tag1 }}
      </span>
    </div>
    <div class="col-md-2 p-2">
      <span class="text-center p-2">
        {{ tag2 }}
      </span>
    </div>
    <div class="col-md-2 p-2">
      <span class="text-center p-2">
        {{ tag3 }}
      </span>
    </div>

    <!-- Image section -->
    <div class="col-md-6">
      <img class="w-100 rounded" :src="imageUrl" alt="Project Image">
    </div>

    <!-- Description -->
    <div class="col-md-6 align-content-center">
      <p class="p-5">{{ description }}</p>
    </div>
  </div>
</template>


<style lang="scss">
span {
  color: gray;
  background-color: #c1c1c1;
  border-radius: 1rem;
  align-content: center;
}
</style>