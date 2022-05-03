<template>
    <main>
        <div class="main_content">
            Content Goes here!
        </div>
        <div class="call_to_actions">
            <div class="actions container">
                <div class="action">
                    <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>
                <div class="action">
                    <img src="@/assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </div>
                <div class="action">
                    <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </div>
                <div class="action">
                    <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </div>
                <div class="action">
                    <img src="@/assets/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </div>
            </div>
        </div>
    </main>
</template>



<script>
export default {
    name: 'SiteMain'
}
</script>


<style scoped lang="scss">
    .main_content{
        height: 100px;
        background-color: black;
    }
    .call_to_actions{
        background-color: rgba(2, 130, 249, 1);
        color: white;
        .actions{
        height: 200px;
        display: flex;
        justify-content: space-around;
        .action{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100%;
            span{
                margin-left: 1rem;
            }
        }
        img{
            height: 60px;
        }
    }
    }
    
</style>