<script>
import MainComic from './MainComic.vue';
import LoadMoreButton from './LoadMoreButton.vue';

export default {
    components: { MainComic, LoadMoreButton },
    props: {
        comics: Array
    }
}
</script>

<template>
    <div class="container">
        <div class="current-series button">CURRENT SERIES</div>
        <div class="flex-container">
            <MainComic v-for="comic in comics" :comic="comic" />
        </div>
        <div class="button-container">
            <LoadMoreButton />
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '@/assets/scss/vars' as *;


.current-series {
    font-size: 1.4rem;
    position: absolute;
    left: 250px;
    transform: translateY(-50%);
}

.flex-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 2rem 0;

    .card {
        flex: 0 0 calc(100% / 6);
    }
}

.button-container {
    display: flex;
    justify-content: center;
}

.button {
    text-align: center;
    background-color: $dc-blue;
    padding: .75rem 5rem;
    font-family: $secondary-font;
    font-weight: 900;
    color: white;
    cursor: pointer;
}
</style>