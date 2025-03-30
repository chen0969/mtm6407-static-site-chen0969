<script setup>
defineProps({
    title: String,
    tagline: String,
    link: String
});
</script>

<template>
    <NuxtLink class="col-md-3 o-card" :to="link">
        <div class="border rounded m-1 p-3 o-card__card">
            <h2 class="o-card__word">{{ title }}</h2>
            <h4 class="o-card__word">{{ tagline }}</h4>
        </div>
    </NuxtLink>
</template>

<style lang="scss">
.o-card {
    text-decoration: none;

    &__card {
        transform-origin: 50% 50%;
        transition: 0.2s;
        cursor: pointer;

        &:hover {
            transform: scale(1.1);
        }
    }
}
</style>