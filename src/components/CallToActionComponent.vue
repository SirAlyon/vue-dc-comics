<template>
        <div class="call_to_actions">
            <div class="actions container">
                <div class="action" v-for="({text, src}, index) in actions" :key="index">
                    <img :src="src" :alt="text">
                    <span>{{text}}</span>
                </div>
            </div>
        </div>
</template>

<script>

export default {
    name: 'CallToAction',
    data() {
        return {
            actions: [
                {
                    src: require('@/assets/img/buy-comics-digital-comics.png'),
                    text: 'DIGITAL COMICS'
                },
                {
                    src: require('@/assets/img/buy-comics-merchandise.png'),
                    text: 'DC MERCHANDISE'
                },
                {
                    src: require('@/assets/img/buy-comics-subscriptions.png'),
                    text: 'SUBSCRIPTION'
                },
                {
                    src: require('@/assets/img/buy-comics-shop-locator.png'),
                    text: 'COMIC SHOP LOCATOR'
                },
                {
                    src: require('@/assets/img/buy-dc-power-visa.svg'),
                    text: 'DC POWER VISA'
                }
            ]
        }
    }
}
</script>

<style scoped lang="scss">
    .call_to_actions{
        background-color: rgba(2, 130, 249, 1);
        color: white;
        position: relative;
        z-index: 2;
        .actions{
        height: 170px;
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
