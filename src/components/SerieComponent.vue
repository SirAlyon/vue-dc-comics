<template>
    <div class="col-2" >
        <div class="serie-logo">
            <img :src="thumb" :alt="series">
            <div class="price">{{price}}</div>
        </div>
        <div class="serie-title">{{series}}</div>
    </div>
</template>

<script>
export default {
    name: 'SerieComponent',
    props: {
        thumb: String,
        series: String,
        price: [Number, String]
    }
}
</script>


<style scoped lang="scss">

        .col-2{
            width: calc(100% / 12) * 2;          
            padding:1rem;
            margin-top: 2rem;
            position: relative; //for price badge
        }
        img{  
            width: 100%;
            max-height: 100%;
            object-fit: cover;
            object-position: top;
            aspect-ratio: 1 / 1;
            //height: auto;
            transition: linear 0.4s;
            &:hover{
                opacity: 0.8;
            }
            &:hover + .price{
                display: block;
            }
        }
        .serie-logo{
            position: relative; //for price badge
        }
        .serie-title{
            //font-size: 1.1rem;
            color: white;
            text-transform: uppercase;
        }

        .price{
            position: absolute;
            right: 0;
            bottom: 10%;
            border-top-left-radius: 10px;
            border-bottom-left-radius: 10px;
            padding: 0.5rem 1rem;
            background-color:rgba(171, 47, 47, 0.911);
            display: none;
        }
        img:hover .price{
            display: block;
        }
</style>