<script setup>
defineProps({
    title: String,
    link: String,
    icon: String
});
</script>

<template>
    <a class="col-md-3 o-social" :href="link" target="_blank">
        <div class="border rounded m-1 p-3 o-social__card">
            <h2 class="o-card__word">{{ title }}</h2>
            <i class="bi o-social__icon" :class="[icon]"></i>
        </div>
    </a>
</template>

<style lang="scss">
.o-social{
    display: block;
    text-decoration: none;
    transition: 0.2s;
    &__card{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    &__icon{
        font-size: var(--text-4xl);
    }
    &:hover{
        transform: translateY(var(--spacing-12));
    }
}
</style>