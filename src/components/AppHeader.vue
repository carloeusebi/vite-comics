<script>
import HeaderLogo from './header/HeaderLogo.vue'
import HeaderNavbar from './header/HeaderNavbar.vue'

export default {
    components: { HeaderLogo, HeaderNavbar }
}
</script>

<template>
    <header>
        <div class="container">
            <HeaderLogo />
            <HeaderNavbar />
        </div>
    </header>
</template>

<style scoped>
header {
    margin: 1rem 0;
}

.container {
    display: flex;
    justify-content: space-between;
}
</style>