<template>
  <div class="container-xxl my-5">
    <div class="row">
      <div class="header-content">
        <div class="col-5 title-description">
          <h1 class="judul">
            Best Technology Service For You In 4.0 in The World
          </h1>
          <p class="mt-3 fw-light">
            A website that serves services in the form of Development<br />
            to Web Scraping services
          </p>
          <a
            href="https://api.whatsapp.com/send?phone=6285156012600&text=Halo%20Admin!%0ASaya%20ingin%20order%20jasa%20Anda"
            class="btn btn-primary mt-5">
            I need data
          </a>
          <a
            href="https://wa.me/6285156012600"
            class="btn btn-outline-secondary mt-5 ms-3">
            I need web development
          </a>
        </div>
        <div class="col-7 me-4 header-right">
          <img src="../assets/foto/banner.png" alt="logo" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Header",
  };
</script>

<style>
  .container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
  }

  .header-content {
    display: flex;
    justify-content: space-between;
  }

  .title-description {
    text-align: left;
  }
  .title-description h1 {
    color: #fff;
    font-size: 54px;
  }
  .judul {
    font-weight: 600;
  }
  .title-description p {
    color: #b3b3b3;
    font-size: 16px;
    font-weight: 300;
  }

  .header-right {
    display: flex;
    /* align-items: center; */
  }

  .header-right img {
    height: 400px;
    margin-left: 105px;
    width: 650px;
  }
</style>
