<template>
    <div class="hello">
        <h1>{{titolo}}</h1>
    </div>
</template>

<script>
export default({
    name: 'Title',
    props: {
        titolo: String
    }
})
</script>
