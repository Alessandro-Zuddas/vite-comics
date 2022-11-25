<script>
  export default {
    data() {
      return {};
    },
  };
</script>

<template>
  <div class="row">
    <div class="hero-img"></div>
  </div>
</template>

<style lang="scss" scoped>
  .row {
    background-color: var(--second-color);
  }

  .container-md {
    display: flex;
    justify-content: flex-start;
  }

  .hero-img {
    width: 100%;
    height: 15.625rem;
    background-image: url("../assets/img/jumbotron.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;
  }

  img {
    width: 100%;
    max-height: 15.625rem;
  }
</style>
