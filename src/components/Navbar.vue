<!--  -->
<template>
  <nav class="navbar">
        <div class="navbar-container">
          <div class="navbar-brand">
            <a href="">
              <img src="../assets/logo.svg" alt="Starbucks" />
            </a>
          </div>

          <ul class="navbar-nav-left">
            <li>
              <a href="#">Menu</a>
            </li>
            <li>
              <a href="#">Rewards</a>
            </li>
            <li>
              <a href="#">Gift Cards</a>
            </li>
          </ul>

          <ul class="navbar-nav-right">
            <li>
              <a href="#">
                <img src="../assets/marker.svg" alt="">
                <span>Find a store</span>
              </a>
            </li>
            <li><button class="btn btn-dark-outline">Sign in</button></li>
            <li><button class="btn btn-dark">Join now</button></li>
          </ul>

          <!-- Hamburger Menu  -->
          <button type="button" class="hamburger">

          </button>
        </div>
      </nav>
</template>

<script>
export default {
  name:"navbar",
  data () {
    return {
    }
  }
}
</script>

<style  scoped src="../assets/styles/variable.css">

</style>
