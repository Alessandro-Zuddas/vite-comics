<script>
  export default {
    data() {
      return {
        objs: [
          {
            name: "DIGITAL COMICS",
            icon: "src/assets/img/buy-comics-digital-comics.png",
          },
          {
            name: "DC MERCHANDISE",
            icon: "src/assets/img/buy-comics-merchandise.png",
          },
          {
            name: "SUBSCRIPTION",
            icon: "src/assets/img/buy-comics-subscriptions.png",
          },
          {
            name: "COMIC SHOP LOCATION",
            icon: "src/assets/img/buy-comics-shop-locator.png",
          },
          {
            name: "DC POWER VISA",
            icon: "src/assets/img/buy-dc-power-visa.svg",
          },
        ],
      };
    },
  };
</script>

<template>
  <div class="row">
    <div class="container-md">
      <div v-for="(obj, index) in objs">
        <img :src="`${obj.icon}`" alt="Icon" />
        <strong>{{ obj.name }}</strong>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .row {
    position: relative;
    z-index: 100;
    background-color: var(--first-color);
  }

  .container-md {
    display: flex;
    justify-content: space-between;
  }

  div {
    display: flex;
    align-items: center;
    padding-top: var(--padd-xl);
    padding-bottom: var(--padd-xl);
  }

  img {
    width: 4.6875rem;
    padding-right: var(--padd-sm);
  }

  strong {
    font-size: 0.9375rem;
    padding-right: var(--padd-xxl);
  }
</style>
