<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-secondary text-uppercase fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand js-scroll-trigger" href="#page-top">
          <img src="~/assets/logo.png" alt="Logo AKSi+" style="height: 50px">
        </a>
        <button class="navbar-toggler navbar-toggler-right text-uppercase font-weight-bold bg-primary text-white rounded collapsed" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item mx-0 mx-lg-1">
              <!-- <a class="nav-link py-3 px-0 px-lg-3 rounded js-scroll-trigger" href="#portfolio">Portfolio</a> -->
              <a class="nav-link py-3 px-0 px-lg-3 rounded js-scroll-trigger" href="#home">Home</a>
            </li>
            <li class="nav-item mx-0 mx-lg-1">
              <!-- <a class="nav-link py-3 px-0 px-lg-3 rounded js-scroll-trigger" href="#portfolio">Portfolio</a> -->
              <a class="nav-link py-3 px-0 px-lg-3 rounded js-scroll-trigger" href="#product">Products</a>
            </li>
            <li class="nav-item mx-0 mx-lg-1">
              <a class="nav-link py-3 px-0 px-lg-3 rounded js-scroll-trigger" href="#about">About Us</a>
            </li>
            <li class="nav-item mx-0 mx-lg-1">
              <a class="nav-link py-3 px-0 px-lg-3 rounded js-scroll-trigger" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>

import Logo from '../../components/Logo'

export default {
  components: {
    Logo
  }
}
</script>

<style>
 .navbar.transparent.navbar-inverse .navbar-inner {
   background: rgba(0,0,0,0.4);
}
</style>
