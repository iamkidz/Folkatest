<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid" id="halaman-container" >
    <form class="d-flex" id="form-search">
        <input class="form-control me-2" type="search" placeholder="Cari Produk" aria-label="Search">
        <div id="kaca-pembesar">
        <i class="fa-solid fa-magnifying-glass"></i>
        </div>
      </form>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li>
            <i class="fa-solid fa-heart" id="hati"></i>
        </li>
        <li class="nav-item">
          <i class="fa-solid fa-suitcase-rolling" id="tas"></i>
        </li>
        <li class="nav-item dropdown" id="user">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
        <i class="fa-solid fa-user" ></i>
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</nav>
<!-- Batas Nav -->

<div class="belanja-wrap" style="width: 100%; background-color:#F5F5F5">
  <div class="dropdown mt-5" style="margin-left: 60px;">
  <button style="width:150px; height: 50px; box-shadow: none;" class="btn btn-danger dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Belanja
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <a class="dropdown-item" href="#">Action</a>
    <a class="dropdown-item" href="#">Another action</a>
    <a class="dropdown-item" href="#">Something else here</a>
  </div>
</div>
</div>
</template>

<style>

  #halaman-container {
    position: fixed;
  }

  #kaca-pembesar {
    position: absolute;
    background: #EB3F36;
    border-radius: 0px 9px 9px 0px;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    line-height: auto;
    width: 40px;
  }

  #hati {
    
    position: absolute;
    top: 13px;
    right: 120px;

  }

  #tas {
    
    position: absolute;
    top: 13px;
    right: 90px;
  }

  #user {
    
    position: absolute;
    top: 1px;
    right: 40px;
  }

  #form-search {
    display: flex;
    justify-content: flex-end;
    position: absolute;
    top: 0;
    right: 150px;
  }

</style>