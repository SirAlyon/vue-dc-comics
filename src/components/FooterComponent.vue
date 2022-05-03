<template>
    <footer>
        <div class="footer_top">
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
                    <div class="col-6 p-relative">
                        <img id="dc_foot_logo" src="@/assets/img/dc-logo-bg.png" alt="">
                    </div>
                </div>
            </div>
        </div>
        <div class="footer_bot">
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <span class="sign-up">SIGN-UP NOW!</span>
                    </div>
                    <div class="col-6">
                        <div class="socials">
                            <span class="follow">FOLLOW US</span>
                            <img src="@/assets/img/footer-facebook.png" alt="">
                            <img src="@/assets/img/footer-twitter.png" alt="">
                            <img src="@/assets/img/footer-youtube.png" alt="">
                            <img src="@/assets/img/footer-pinterest.png" alt="">
                            <img src="@/assets/img/footer-periscope.png" alt="">
                        </div>
                    </div>
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
        color: gray;    
        .footer_top{
            background-image: url('@/assets/img/footer-bg.jpg');
            background-size: cover;
            background-repeat: no-repeat;
        }
        .list_title{
            color: white;
            font-weight: bold;
            font-size: 1.2rem;
        }
        .col-4{
            padding: 0 1rem;
            margin-top: 3rem;
            margin-bottom: 2rem;
        }
        #dc_foot_logo{
            width: 550px;
            position: absolute;
            //transform: translateX(-100%);
            right: 50px;
            top: -100px;
            z-index: 0;
        }
        ul{
            list-style: none;
            padding: 0;
        }
        li:hover{
            color: white;
        }
        .footer_bot{
            //height: 100px;
            background-color: rgba(48, 48, 48, 1);
            position: relative;
            img{
                height: 40px;
                width: auto;
                margin: 0 0.8rem;
            }
            .col-6{
                display: flex;
                align-items: center;
                padding: 1.5rem 0;
            }
            .sign-up{
                color: white;
                border: 1px solid rgba(2, 130, 249, 1);
                padding: 0.8rem;
                font-weight: bold;
            }
            .socials{
                color: rgba(2, 130, 249, 1);
                font-size: 1.2rem;
                font-weight: bold;
                width: 100%;
                display: flex;
                justify-content: flex-end;
                align-items: center;
            }
        }
    }
</style>
