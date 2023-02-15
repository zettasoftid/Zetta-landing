<template>
  <div class="container-xxl my-5">
    <div class="row">
      <div class="header-content">
        <div class="col-5 title-description">
          <h1 class="judul">
            Best Technology Service For You In 4.0 in The World
          </h1>
          <p class="mt-3 fw-light">
            Let's build something great together. Hire our expert team of
            software professionals today and take your business to the next
            level.
          </p>
          <a href="http://wa.me/6281339691260" class="btn btn-primary mt-5">
            I need data
          </a>
          <a
            href="http://wa.me/6281339691260"
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
