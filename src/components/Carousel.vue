<template>
    <div id="carouselExampleIndicators" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://static.nike.com/a/images/c_limit,w_592,f_auto/t_product_v1/daa05e36-2b7e-4057-80d7-3233c8794746/pegasus-41-older-road-running-shoes-z1216h.png">
        </div>
        <div class="carousel-item">
          <img src="https://blue.kumparan.com/image/upload/fl_progressive,fl_lossy,c_fill,q_auto:best,w_640/v1528710003/lakeqtvbs3kantb3mnbd.jpg" >
        </div>
        <div class="carousel-item">
          <img src="https://images.tokopedia.net/img/cache/700/VqbcmM/2020/10/19/fd9f624c-b715-4fe7-8642-144d891dd8f7.jpg">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
      </template>
      
      <script>
      export default {
        name: 'Carousel'
      }
      </script>