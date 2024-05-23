
<template>
    <div class="col-md-4 mb-4">
      <div class="card h-100 shadow-sm">
        <img class="card-img-top" :src="imgUrl" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">{{ title }}</h5>
          <p class="card-text">{{ description }}</p>
          <div class="d-flex justify-content-between align-items-center">
            <button type="button" class="btn btn-primary">View</button>
            <small class="text-muted">9 mins</small>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Card',
    props: {
      title: String,
      description: String,
      imgUrl: String
    }
  }
  </script>
  
  <style scoped>
  .card-img-top {
    height: 200px;
    object-fit: cover;
  }
  
  .card-body {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  </style>