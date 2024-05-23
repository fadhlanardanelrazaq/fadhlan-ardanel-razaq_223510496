<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">fadhlan shoes</a>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Produk
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">shoes</a></li>
                <li><a class="dropdown-item" href="#">pants</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" aria-disabled="true">Pembayaran</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    </template>
    
    <script>
    export default {
      name: 'Navbar'
    }
    </script>
    
    <style scoped>
    .navbar {
      box-shadow: 0 4px 6px rgba(246, 10, 10, 0.1);
    }
    
    .navbar-nav .nav-item .nav-link {
      transition: color 0.3s ease;
    }
    
    .navbar-nav .nav-item .nav-link:hover {
      color: #ff1500;
    }
    </style>