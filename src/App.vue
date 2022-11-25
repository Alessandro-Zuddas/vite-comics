<script>
  import AppHeader from "./components/AppHeader.vue";
  import AppHeroTop from "./components/AppHeroTop.vue";
  import AppHeroBottom from "./components/AppHeroBottom.vue";
  import AppMain from "./components/AppMain.vue";
  import AppFooter from "./components/AppFooter.vue";

  export default {
    components: {
      AppHeader,
      AppHeroTop,
      AppHeroBottom,
      AppMain,
      AppFooter,
    },
  };
</script>

<template>
  <AppHeader />
  <AppHeroTop />
  <AppHeroBottom />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
  @import "./style/global.scss";

  #app {
    max-width: 100vw;
  }
</style>
