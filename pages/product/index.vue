<template>
  <div>
    <section class="page-section bg-default portfolio" id="product" style="background: #fff">
      <div class="container">

        <!-- Portfolio Section Heading -->
        <h2 class="page-section-heading text-center text-uppercase text-secondary mb-0">Our Products</h2>

        <!-- Icon Divider -->
        <div class="divider-custom">
          <div class="divider-custom-line"></div>
          <div class="divider-custom-icon">
            <i class="fas fa-star"></i>
          </div>
          <div class="divider-custom-line"></div>
        </div>

        <!-- Portfolio Grid Items -->
        <div class="row">

          <!-- Portfolio Item 1 -->
          <div class="col-md-6 col-lg-6">
            <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal1">
              <div class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100">
                <div class="portfolio-item-caption-content text-white mr-2 ml-3">
                  <p>Sebuah Platform Edukasi untuk membantu Aktivitas Akademik di Sekolah</p>
                  <br>
                  <a href="" class="btn btn-block btn-danger">ReadMore</a>
                </div>
              </div>
              <img class="img-fluid" src="~/assets/products/Edustar.png" alt="">
            </div>
          </div>

          <!-- Portfolio Item 2 -->
          <div class="col-md-6 col-lg-6">
            <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal2">
              <div class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100">
                <div class="portfolio-item-caption-content text-white mr-2 ml-3">
                  <p><small>Solusi Tuntas Untuk Anda Yang Membutuhkan Sistem Inventori</small></p>
                  <br>
                  <a href="" class="btn btn-block btn-danger">ReadMore</a>
                </div>
              </div>
              <img class="img-fluid" src="~/assets/products/POSmo+.png" alt="">
            </div>
          </div>

        </div>
        <!-- /.row -->

      </div>
    </section>
  </div>
</template>

<script>
export default {

}
</script>
