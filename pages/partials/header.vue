<template>
  <div id="home">
    <!-- <div id="particles-js"><canvas class="particles-js-canvas-el" width="0" height="0" style="width: 100%; height: 100%;background-image: url('https://s.newsweek.com/sites/www.newsweek.com/files/styles/lg/public/2017/09/12/coding-schools-2017.jpg'); "></canvas></div> -->
    <div id="particles-js" style="background-color: rgb(182, 25, 36); background-image: url('https://mcdn.wallpapersafari.com/medium/2/66/Ue1yGJ.jpg'); background-size: cover; background-repeat: no-repeat; background-position: 50% 50%;"><canvas class="particles-js-canvas-el" width="1366" height="395" style="width: 100%; height: 100%;"></canvas></div>
    <header class="masthead text-white text-center" style="height: 650px">

      <div class="row">
        <div class="col-md-6">
          <div class="container d-flex align-items-center flex-column">
            <!-- <h1 class="masthead-heading text-uppercase mb-2">Welcome to</h1> -->
            <img src="~/assets/logo.png" style="height: 170px" class="img-responsive">
          </div>
        </div>
        <div class="col-md-6">
          <div class="jumbotron">
            <h1></h1>
          </div>
        </div>
      </div>


    </header>
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
