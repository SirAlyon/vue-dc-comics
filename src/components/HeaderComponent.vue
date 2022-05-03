<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="col-5">
                    <img src="@/assets/img/dc-logo.png" alt="">
                </div>
                <div class="col-7">
                    <nav>
                        <a href="#" v-for="(link, index) in nav_links" :key="index">{{link}}</a>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>

<script>

export default {
    name: 'SiteHeader',
    data(){
        return{
            nav_links: ['CHARACTERS', 'COMICS', 'MOVIES', 'TV', 'GAMES', 'COLLECTABLES', 'VIDEOS', 'FANS', 'NEWS', 'SHOP']
        }
    }
}
</script>



<style scoped lang="scss">

img{
    align-self: flex-start;
    padding: 1rem;
}
nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 100%;
    padding: 0 1rem;
    a{
        text-decoration: none;
        color: black;
        font-weight: bold;
        height: 100%;
        display: flex;
        align-items: center;
        &:hover{
            border-bottom: 5px solid rgba(2, 130, 249, 1);
            color: rgba(2, 130, 249, 1);
        }
    }
}
    
    
</style>