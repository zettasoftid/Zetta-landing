<template>
  <nav class="navbar navbar-expand-lg navbar-light my-3">
    <div class="container-xxl">
      <a class="navbar-brand" href="#"
        ><img
          src="../assets/foto/Z 1.png"
          alt="logo"
          height="50px"
          width="50px"
      /></a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse justify-content-center"
        id="navbarNav">
        <ul class="navbar-nav mx-3">
          <li class="nav-item mx-3">
            <a class="nav-link bold-text" href="#">Home</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link fw-normal" href="#">Product</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link fw-normal" href="#">Learn</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link fw-normal" href="#">Community</a>
          </li>
        </ul>
      </div>
      <a
        href="https://api.whatsapp.com/send?phone=6285156012600"
        type="button"
        class="btn contact-us">
        Contact us
      </a>
    </div>
  </nav>
</template>

<script>
  export default {
    name: "Navbar",
  };
</script>

<style>
  .navbar .nav-link {
    background: transparent;
    font-size: 16px;
    color: white;
  }
  .bold-text {
    font-weight: 600;
  }
  .fw-normal {
    font-weight: 300;
    color: #f8f9fd;
  }

  .contact-us {
    background-color: #f8f9fd;
    color: #252525;
    border-color: #fff;
    font-weight: bold;
    font-size: 18px;
  }
  .contact-us:hover {
    background-color: #252525;
    color: #ffff;
    border-color: #fff;
    font-weight: bold;
    font-size: 18px;
  }

  .btn-primary {
    background-color: #f8f9fd;
    color: #252525;
    border-color: #fff;
    font-weight: bold;
    font-size: 22px;
  }

  .btn-primary:hover {
    background-color: #252525;
    color: #ffff;
    border-color: #fff;
    font-weight: normal;
    font-size: 22px;
  }

  .btn-outline-secondary {
    font-size: 22px;
  }

  a .img {
    height: 30px;
    width: 30px;
  }
</style>
