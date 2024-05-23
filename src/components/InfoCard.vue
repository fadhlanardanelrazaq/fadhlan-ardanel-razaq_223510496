<template>
    <div class="col-md-4 mb-4">
      <div class="info-card p-3 h-100 shadow-sm">
        <h5>{{ title }}</h5>
        <p>{{ description }}</p>
        <img class="img-fluid" :src="imgUrl" alt="Info image">
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'InfoCard',
    props: {
      title: String,
      description: String,
      imgUrl: String
    }
  }
  </script>
  
  <style scoped>
  .info-card {
    margin-bottom: 20px; /* Tambahkan margin bawah untuk memberi jarak antar InfoCard */
  }
  
  .info-card img {
    margin-top: 15px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
  }
  </style>