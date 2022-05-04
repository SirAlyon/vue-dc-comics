<template>
    <div class="col-2" >
        <div class="serie-logo">
            <img :src="thumb" :alt="series">
        </div>
        <div class="serie-title">{{series}}</div>
    </div>
</template>

<script>
export default {
    name: 'SerieComponent',
    props: {
        thumb: String,
        series: String
    }
}
</script>


<style scoped lang="scss">

        .col-2{
            width: calc(100% / 12) * 2;          
            padding:1rem;
            margin-top: 2rem;
        }
        img{  
            width: 100%;
            max-height: 100%;
            object-fit: cover;
            object-position: top;
            aspect-ratio: 1 / 1;
            //height: auto;
        }
        .serie-title{
            font-size: 1.2rem;
            color: white;
            
        }
</style>