<script>
  export default {
    data() {
      return {};
    },
  };
</script>

<template>
  <div class="card">
    <img src="" alt="" />
    <h4>Titolo</h4>
  </div>
</template>

<style lang="scss" scoped>
  .row {
    background-color: var(--second-color);
  }

  .card {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    width: calc(100% / 6 - 0.625rem);
    padding: 0 0;
    margin-right: 0.625rem;
    margin-bottom: 0.625rem;
    margin-top: 0.625rem;
  }

  img {
    width: 12.5rem;
    height: 12.5rem;
    background-color: aqua;
  }

  h4 {
    padding-top: 0.625rem;
  }
</style>
