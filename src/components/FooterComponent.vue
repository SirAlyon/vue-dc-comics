<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-6 d-flex">
                    <div class="col-4">
                        <div class="list_title">DC COMICS</div>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                        <div class="list_title">DC COMICS</div>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                        
                    </div>
                    <div class="col-4">
                        <div class="list_title">DC</div>
                        <ul>
                            <li>Terms of Use</li>
                            <li>Privacy policy (new)</li>
                            <li>Ad Choices</li>
                            <li>Adversiting</li>
                            <li>Jobs</li>
                            <li>Videos</li>
                            <li>News</li>
                            <li>Privacy policy (new)</li>
                            <li>Ad Choices</li>
                            <li>Adversiting</li>
                            <li>Jobs</li>
                        </ul>
                    </div>
                    <div class="col-4">
                        <div class="list_title">SITES</div>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div>
                <div class="col-6">
                    <img src="@/assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>


<script>
export default {
    name: 'SiteFooter'
}
</script>


<style scoped lang="scss">
    footer{
        background-image: url('@/assets/img/footer-bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        height: 700px;
        color: gray;    
        .list_title{
            color: white;
            font-weight: bold;
            font-size: 1.2rem;
        }
        .col-4{
            padding: 0 1rem;
            margin-top: 3rem;
        }
        img{
            width: 900px;
        }
        ul{
            list-style: none;
            padding: 0;
        }
    }
</style>
