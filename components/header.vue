<template>
    <div class="container-fluid p-2">
        <nav class="rounded p-2 animate__animated animate__backInDown">
        <ul class="row gx-2 justify-content-center">
            <li class="col-2 text-center">
                <NuxtLink class="o-navBtn" to="/design">Design</NuxtLink>
            </li>
            <li class="col-2 text-center">
                <NuxtLink class="o-navBtn" to="/develop">Develop</NuxtLink>
            </li>
            <li class="col-2 text-center">
                <NuxtLink class="o-navBtn" to="/photo">Photo</NuxtLink>
            </li>
            <li class="col-2 text-center">
                <NuxtLink class="o-navBtn" to="/contact">Contact</NuxtLink>
            </li>
            <li class="col-2 text-center">
                <NuxtLink class="o-navBtn" to="/game">Play a Game</NuxtLink>
            </li>
        </ul>
    </nav>
    </div>
</template>

<style lang="scss">
nav {
    background-color: black;

    ul {
        list-style: none;
    }
}

.o-navBtn {
    all: unset;
    color: gray;
    transition: 0.1s;
    cursor: pointer;
    &:hover {
        color: white;
        font-size: 1.2rem;
    }
}
</style>