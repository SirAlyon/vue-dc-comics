<template>
    <div class="jumbotron">
        <img :src="thumb" alt="">
    </div>
</template>

<script>

export default {
    name: 'JumbotronComponent',
    props: {
        thumb: String
    }
}

</script>

<style scoped lang="scss">
    .jumbotron{
    height: 400px;
    overflow: hidden;
    }
</style>