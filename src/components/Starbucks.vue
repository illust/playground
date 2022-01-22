<template>
    <div class="container">
      <navbar></navbar>
      
      <!-- Mobile Menu -->
      <div class="mobile-menu hidden" id="menu"></div>

      <!-- Box A -->
      <section class="box box-a bg-primary text-center py-md">
        <div class="box-inner">
          <h2 class="text-xl">Jingle all the ways to free favorites</h2>
          <p class="text-md">
            Join StarBucks Rewards for delicious deals & exclusive offers.
            <a href="#">Learn more</a> 
          </p>
        </div>
      </section>

      <!-- Box B -->
      <section class="box box-b bg-secondary grid-col-2">
        <img src="../assets/box-b.png" alt="" />
        <div class="box-text">
          <h2 class="text-xl">New to the nice list</h2>
          <p class="text-md">For a nondairy twist on a holiday cookie classic,
            try the new Iced Sugar Cookie Almondmilk Latte.
          </p>
          <a href="#" class="btn btn-light-outline">Order Now</a>
        </div>
      </section>

      <!-- Box C  -->
      <section class="box box-c bg-secondary grid-col-2 grid-reversed">
        <img src="../assets/box-c.png" alt=""/>
        <div class="box-text">
          <h2 class="text-xl">Merry monent</h2>
          <p class="text-md">
            Treat yourself to a festive Sugar Plum Cheese Danish with a nicely
            spiced sugar-plum spread.
          </p>
          <a href="#" class="btn btn-light-outline">Order Now</a>
        </div>
      </section>

      <!-- Box D  -->
      <section class="box box-d bg-primary grid-col-2 grid-col-2">
        <img src="../assets/box-d.png" alt="">
        <div class="box-text">
          <h2 class="text-xl">Starbucks Thanksgiving Blend</h2>
          <p class="text-md">
            This elegant dark roast returns,showcasing flavors from some of the
              world's major coffee-growing regions.
          </p>
          <a href="#" class="btn btn-light-outline">Order Now</a>
        </div>
      </section>
      <!-- Box E  -->
      <section class="box box-e bg-secondary grid-col-2 grid-reversed">
        <img src="../assets/box-e.jpg" alt="">
        <div class="box-text">
          <h2 class="text-md">Fighting hunger this holiday</h2>
          <p class="text-sm">
            Hunger is affecting millions of people across America this holiday
            season. Join us in our commitment to hunger relief and help feed
            neighbors in need.
          </p>
          <a href="#" class="btn btn-light-outline">Order Now</a>
        </div>
      </section>
      <!-- Box F  -->
      <section class="box box-f grid-col-2">
        <div>
          <img src="../assets/box-f1.jpg" alt="">
          <div class="bg-extra py-lg">
            <div class="box-text">
              <h2 class="text-md">Let the holiday cheer come to you</h2>
              <p class="text-sm">
                Make the moment merry.Order Starbucks holiday favorites on Uber
                Eats.*
              </p>
              <a href="#" class="btn btn-dark-outline">Order Now</a>
            </div>
          </div>
        </div>
        <div>
          <img src="../assets/box-f2.jpg" alt="">
          <div class="bg-primary py-lg">
            <div class="box-text">
              <h2 class="text-md">Loved Passing on Netflix?</h2>
              <p class="text-sm">
                Our new social series about film adaptations kicks off with
                the actors and directors who brought the book to life.
              </p>
              <a href="#" class="btn btn-light-outline">Order Now</a>
            </div>
          </div>
        </div>
      </section>
      
      <div class="divider"></div>

      <footer class="footer">
        <div class="footer-container">
          <div class="social">
            <a href="https://spotify.com" class="">
              <img src="" alt="">
            </a>
          </div>
          <div class="social">
            <a href="https://google.com" class="">
              <img src="" alt="">
            </a>
          </div>
        </div>
      </footer>
    </div>
</template>

<script>
import navbar from './Navbar.vue'
export default {
  components: { navbar },
  name: 'Starbucks',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="../assets/styles/variable.css">

</style>
