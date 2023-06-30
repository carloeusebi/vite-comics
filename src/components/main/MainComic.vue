<script>
export default {
}
</script>

<template>
    <div class="card">
        <figure>
            <img src="https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY"
                alt="">
        </figure>
        <h4> ACTION COMICS</h4>
    </div>
</template>

<style scoped>
.card {
    padding: 0 1rem;
    margin: 2rem 0;
    cursor: pointer;
}

figure {
    height: 175px;
    overflow: hidden;
}

img {
    width: 100%;
    height: 150%;
    object-fit: cover;
    object-position: top center;
}

h4 {
    color: white;
    text-transform: uppercase;
    margin-top: 1rem;
    font-weight: normal;
    font-size: .8rem;
}
</style>