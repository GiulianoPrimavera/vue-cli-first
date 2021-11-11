<template>
    <div class="hello">
        <h1 class="hero">{{ hero }}</h1>
    </div>
</template>

<script>
export default {
    name: 'Hero',
    props:{
        hero: String
    }
}
</script>

<style scoped>
    .hero{
        color: red;
        font-size: 200px;
    }
</style>>
