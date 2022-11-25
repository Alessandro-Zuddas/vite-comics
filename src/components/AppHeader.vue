<script>
  export default {
    data() {
      return {};
    },
  };
</script>

<template>
  <div class="row">
    <div class="container-md">
      <img src="../assets/img/dc-logo.png" alt="" />
      <nav>
        <ul>
          <li>
            <a href="#"><small>CHARACTERS</small></a>
          </li>
          <li>
            <a href="#"><small class="active">COMICS</small></a>
          </li>
          <li>
            <a href="#"><small>MOVIES</small></a>
          </li>
          <li>
            <a href="#"><small>TV</small></a>
          </li>
          <li>
            <a href="#"><small>GAMES</small></a>
          </li>
          <li>
            <a href="#"><small>COLLECTIBLES</small></a>
          </li>
          <li>
            <a href="#"><small>VIDEOS</small></a>
          </li>
          <li>
            <a href="#"><small>FANS</small></a>
          </li>
          <li>
            <a href="#"><small>NEWS</small></a>
          </li>
          <li>
            <a href="#"><small>SHOP</small></a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .row {
    background-color: white;
  }

  .container-md {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  img {
    width: 6.25rem;
    padding: var(--padd-xl);
  }

  ul {
    display: flex;
    list-style: none;
  }

  li {
    padding-left: var(--padd-xl);
  }

  a {
    text-decoration: none;
    color: black;
  }

  .active {
    color: var(--first-color);
    border-bottom: 5px solid var(--first-color);
    padding-bottom: 2.375rem;
  }
</style>
