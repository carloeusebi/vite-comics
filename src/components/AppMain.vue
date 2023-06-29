<script>
import MainContent from './main/MainContent.vue';

export default {
    components: { MainContent }
}
</script>

<template>
    <main>
        <MainContent />
    </main>
</template>

<style scoped>
main>* {
    height: 200px;
}
</style>