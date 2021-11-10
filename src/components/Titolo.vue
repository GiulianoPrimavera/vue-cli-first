<template>
    <div class="hello">
        <h1>{{titolo}}</h1>
    </div>
</template>

<script>
export default({
    name: 'Titolo',
    props: {
        titolo: String
    }
})
</script>
