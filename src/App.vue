<template>
  <div id="app">
    <SiteHeader />
    <SiteMain />

    
  </div>
</template>

<script>
import SiteHeader from '@/components/HeaderComponent.vue'
import SiteMain from '@/components/MainComponent.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain
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

.col-5{
    width: calc(100% / 12) * 5;
}

.col-7{
    width: calc(100% / 12) * 7;
}

/* ROOT Colors */
:root{
  --primary: rgba(2, 130, 249, 1);
}
</style>
