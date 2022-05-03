<template>
  <div id="app">
    <SiteHeader />
    <SiteMain />
    <SiteFooter />
    
  </div>
</template>

<script>
import SiteHeader from '@/components/HeaderComponent.vue'
import SiteMain from '@/components/MainComponent.vue'
import SiteFooter from '@/components/FooterComponent.vue'


export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
}

/* Common */
img{
  max-width: 100%;
}

.container{
    margin: auto;
    max-width: 1440px;
}
  
.row{
    display: flex;
    flex-wrap: wrap;
    margin-left: -1rem;
    margin-right: -1rem;
}
  
.col{
    flex-grow: 1;
}

.col-4{
    width: calc(100% / 12) * 4;
}

.col-5{
    width: calc(100% / 12) * 5;
}

.col-6{
    width: calc(100% / 12) * 6;
}

.col-7{
    width: calc(100% / 12) * 7;
}

.col-8{
    width: calc(100% / 12) * 8;
}

/* Utility */
.d-flex{
  display: flex;
}

.align-end{
  text-align: end;
}

/* ROOT Colors */
:root{
  --primary: rgba(2, 130, 249, 1);
}
</style>
