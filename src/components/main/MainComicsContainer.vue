<script>
import MainComic from './MainComic.vue';

export default {
    components: { MainComic }
}
</script>

<template>
    <div class="container">
        <div class="flex-container">
            <MainComic v-for="i in 12" />
        </div>
    </div>
</template>

<style lang="scss" scoped>
.flex-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: 5rem 0;

    .card {
        flex: 0 0 calc(100% / 6);
    }
}
</style>