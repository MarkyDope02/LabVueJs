<template>
  <div>

    <nav>
      <div class="navbar">
        <div class="container nav-container">
          <input class="checkbox" type="checkbox" name="" id="" />
          <div class="hamburger-lines">
            <span class="line line1"></span>
            <span class="line line2"></span>
            <span class="line line3"></span>
          </div>
          <div class="logo">
            <h1>CARS</h1>
          </div>
          <div class="menu-items">
              <ul id="links"><router-link to="/" tag="li" exact>Home</router-link></ul>
              <ul id="links"><router-link to="/login" tag="li" exact>LogIn</router-link></ul>
              <ul id="links"><router-link to="/shop_info" tag="li" exact>Shop Info</router-link></ul>
              <ul id="links"><router-link to="/about" tag="li" exact>About</router-link></ul>
              <ul id="links"><router-link to="/manage" tag="li" exact>Manage</router-link></ul>
          </div>
        </div>
      </div>
    </nav>
    <div>
      <div class="hero">
        <div class="container" style="background-image:url(https://i.pinimg.com/originals/95/ef/b8/95efb8425d270933e5e890b33ab5ef70.gif)">
          <div class="row justify-content-between">
            <div class="col-lg-5">
              <div class="intro-excerpt">

                <p class="mb-4">Cars are motor vehicles designed for passenger transportation. They come in various types, run on fuels like gasoline or electricity, and are manufactured by companies like Toyota and Ford. They offer personal mobility, have safety features, and impact the environment. Innovations include electric cars and autonomous vehicles. </p>
                <p>
                <h5 href="/shop" class="btn btn-secondary me-2">Shop Now</h5>
                </p>
              </div>
            </div>


            </div>
          </div>
        </div>
      </div>
    </div>


</template>

<script>
//Modified by Caibal
export default {
  name: "Top",
  data() {
    return {
      open: false,
    }
  },
  methods: {

    menubar: function () {
      if (this.open) {
        this.open = false;
        return this.open;
      } else {
        this.open = true;
        return this.open;
      }
    }
  },
};
//Ends
</script>
