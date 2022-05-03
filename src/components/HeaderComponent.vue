<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="col-5">
                    <img src="@/assets/img/dc-logo.png" alt="">
                </div>
                <div class="col-7">
                    <nav>
                        <a href="#">CHARACTERS</a>
                        <a href="#">COMICS</a>
                        <a href="#">MOVIES</a>
                        <a href="#">TV</a>
                        <a href="#">GAMES</a>
                        <a href="#">COLLECTIBLES</a>
                        <a href="#">VIDEOS</a>
                        <a href="#">FANS</a>
                        <a href="#">NEWS</a>
                        <a href="#">SHOP</a>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>

<script>

export default {
    name: 'SiteHeader'
}
</script>



<style scoped lang="scss">
header{
    padding: 1rem;
}
img{
    align-self: flex-start;
    padding-left: 1rem;
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
        &:hover{
            color: blue;
        }
    }
}
    
    
</style>