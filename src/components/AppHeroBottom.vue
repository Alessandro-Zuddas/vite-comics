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
    <button>LOAD MORE</button>
  </div>
</template>

<style lang="scss" scoped>
  .row {
    background-color: var(--second-color);
  }

  .container-md {
    position: relative;
    display: flex;
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

  button {
    margin-bottom: 1.25rem;
    background-color: var(--first-color);
    border-radius: 0;
    padding: 0.3125rem 1.5625rem;
  }
</style>
