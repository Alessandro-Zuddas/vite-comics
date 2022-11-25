<script>
  export default {
    data() {
      return {};
    },
  };
</script>

<template>
  <!-- Footer Top -->
  <div class="row ft-top-row">
    <div class="container-md footer-top">
      <div>
        <ul>
          <li>
            <h3>DC COMICS</h3>
          </li>
          <li>
            <h6>Comics</h6>
          </li>
          <li>
            <h6>Movies</h6>
          </li>
          <li>
            <h6>TV</h6>
          </li>
          <li>
            <h6>Games</h6>
          </li>
          <li>
            <h6>Videos</h6>
          </li>
          <li>
            <h6>News</h6>
          </li>
        </ul>
        <ul class="ul-bottom">
          <li>
            <h3>SHOP</h3>
          </li>
          <li>
            <h6>Shop DC</h6>
          </li>
          <li>
            <h6>Shop DC collectibles</h6>
          </li>
        </ul>
      </div>
      <div class="list-col">
        <ul>
          <li>
            <h3>DC</h3>
          </li>
          <li>
            <h6>Comics</h6>
          </li>
          <li>
            <h6>Movies</h6>
          </li>
          <li>
            <h6>TV</h6>
          </li>
          <li>
            <h6>Games</h6>
          </li>
          <li>
            <h6>Videos</h6>
          </li>
          <li>
            <h6>News</h6>
          </li>
          <li>
            <h6>Comics</h6>
          </li>
          <li>
            <h6>Movies</h6>
          </li>
          <li>
            <h6>TV</h6>
          </li>
          <li>
            <h6>Games</h6>
          </li>
        </ul>
      </div>
      <div class="list-col">
        <ul>
          <li>
            <h3>SITES</h3>
          </li>
          <li>
            <h6>Comics</h6>
          </li>
          <li>
            <h6>Movies</h6>
          </li>
          <li>
            <h6>TV</h6>
          </li>
          <li>
            <h6>Games</h6>
          </li>
          <li>
            <h6>Videos</h6>
          </li>
        </ul>
      </div>
      <div class="bg-logo">
        <img
          class="bg-logo"
          src="src/assets/img/dc-logo-bg.png"
          alt="DC-BG-Logo"
        />
      </div>
    </div>
  </div>

  <div class="row ft-bottom-row">
    <!-- Footer Bottom -->
    <div class="container-md footer-bottom">
      <button>
        <small>SING-UP NOW!</small>
      </button>
      <div class="ft-bottom-list">
        <h5>FOLLOW US</h5>
        <a href="">
          <img src="src/assets/img/footer-facebook.png" alt="Social Icon" />
        </a>
        <a href="">
          <img src="src/assets/img/footer-twitter.png" alt="Social Icon" />
        </a>
        <a href="">
          <img src="src/assets/img/footer-youtube.png" alt="Social Icon" />
        </a>
        <a href="">
          <img src="src/assets/img/footer-pinterest.png" alt="Social Icon" />
        </a>
        <a href="">
          <img src="src/assets/img/footer-periscope.png" alt="Social Icon" />
        </a>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .ft-top-row {
    background-image: url("src/assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }

  .footer-top {
    display: flex;
    justify-content: flex-start;
  }

  .footer-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  ul {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    list-style: none;
    padding-top: var(--padd-xxl);
  }

  h3 {
    color: white;
  }

  .ul-bottom {
    padding-bottom: var(--padd-xxl);
  }

  .list-col {
    padding-left: 3.125rem;
  }

  .bg-logo {
    position: absolute;
    top: 70%;
    right: 17%;
    width: 45%;
  }

  .ft-bottom-row {
    position: relative;
    z-index: 100;
    background-color: var(--third-color);
    padding-top: var(--padd-xl);
    padding-bottom: var(--padd-xl);
  }

  button {
    background-color: inherit;
    border: 1px solid var(--first-color);
    border-radius: 0;
  }

  h5 {
    color: var(--first-color);
  }

  .ft-bottom-list {
    display: flex;
    align-items: center;
  }

  a {
    padding-left: var(--padd-xl);
  }

  img {
    width: 1.25rem;
  }
</style>
