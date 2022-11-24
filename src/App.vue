<script>

import AppHeader from './components/AppHeader.vue'
import AppHero from './components/AppHero.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppHero,
    AppMain,
    AppFooter
  }
}

</script>

<template>

  <AppHeader/>
  <AppHero/>
  <AppMain/>
  <AppFooter/>

</template>

<style lang="scss">

  @import "./style/global.scss";

</style>
