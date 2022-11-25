<script>
  import ProductsCards from "./ProductsCards.vue";

  export default {
    data() {
      return {};
    },
    components: {
      ProductsCards,
    },
  };
</script>

<template>
  <div class="row">
    <div class="container-md">
      <strong>Current Series</strong>
      <ProductsCards />
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .row {
    background-color: var(--second-color);
  }

  .container-md {
    position: relative;
    display: flex;
    justify-content: flex-start;
    flex-wrap: wrap;
    padding-top: 2.5rem;
    padding-bottom: 2.5rem;
  }

  strong {
    position: absolute;
    top: -3%;
    left: -1%;
    font-size: large;
    padding: 0.3125rem 0.75rem;
    background-color: var(--first-color);
  }
</style>
