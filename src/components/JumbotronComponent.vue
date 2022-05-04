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
    height: 550px;
    overflow: hidden;
    img{
        width: 100%;
        object-position: top;
        object-fit: cover;
    }
    }
</style>