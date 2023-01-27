<template>
  <div class="container-xxl my-5">
    <div class="row">
      <div class="section-content">
        <h2 class="section-title">Our Product and Service</h2>
        <p>
          A website that serves services in the form of Development to Web
          Scraping services
        </p>
      </div>
      <div class="card my-4" style="width: 18rem">
        <img
          src="../assets/svg/Scraping.svg"
          class="card-img-top"
          alt="uiux-icon" />
        <div class="card-body">
          <h5 class="card-title">Data Extraction Service</h5>
          <p class="card-text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
            orci quis massa non mi, sed iaculis leo aenean.
          </p>
          <a href="#" class="btn btn-content">Learn more</a>
        </div>
      </div>
      <div class="card my-4 web-analysis" style="width: 18rem">
        <img
          src="../assets/svg/Scraping.svg"
          class="card-img-top"
          alt="uiux-icon" />
        <div class="card-body">
          <h5 class="card-title">Web Analysis</h5>
          <p class="card-text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
            orci quis massa non mi, sed iaculis leo aenean.
          </p>
          <a href="#" class="btn btn-content mt-4">Learn more</a>
        </div>
      </div>
      <div class="card my-4 smart-browser" style="width: 18rem">
        <img
          src="../assets/svg/code.svg"
          class="card-img-top"
          alt="uiux-icon" />
        <div class="card-body">
          <h5 class="card-title">Smart Browser</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
          <a href="#" class="btn btn-content mt-4">Learn more</a>
        </div>
      </div>
      <br />
      <div class="card my-4 uiux" style="width: 18rem">
        <img
          src="../assets/svg/uiux.svg"
          class="card-img-top"
          alt="uiux-icon" />
        <div class="card-body">
          <h5 class="card-title">UI/UX Design</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
          <a href="#" class="btn btn-content">Learn more</a>
        </div>
      </div>
      <div class="card my-4 webdev" style="width: 18rem">
        <img
          src="../assets/svg/code.svg"
          class="card-img-top"
          alt="uiux-icon" />
        <div class="card-body">
          <h5 class="card-title">Web Development</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
          <a href="#" class="btn btn-content">Learn more</a>
        </div>
      </div>
      <div class="card my-4 mobiledev" style="width: 18rem">
        <img
          src="../assets/svg/mobiledev.svg"
          class="card-img-top"
          alt="uiux-icon" />
        <div class="card-body">
          <h5 class="card-title">Mobile Development</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
          <a href="#" class="btn btn-content">Learn more</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Section",
  };
</script>

<style>
  .container {
    margin-bottom: 60px;
  }
  .section-content {
    color: #fff;
  }
  .section-content h2 {
    font-size: 34px;
    font-weight: 600;
  }
  .section-content p {
    color: #b3b3b3;
    margin-top: 12px;
    font-size: 16px;
    font-weight: 300;
  }
  .card {
    align-items: right;
    border-color: #e2e2e2;
    background-color: #333;
    color: #f8f9fd;
  }
  .card-img-top {
    padding-top: 10px;
    height: 80px;
    width: 80px;
  }
  .card-title {
    font-size: 24px;
    font-weight: 500;
  }
  .card p {
    font-size: 12px;
    font-weight: 300;
    color: #b3b3b3;
  }
  .btn-content {
    font-size: 18px;
    font-weight: 400;
    background-color: transparent;
    border-color: #6666;
    color: #fff;
  }
  .btn-content:hover {
    font-size: 18px;
    font-weight: 400;
    background-color: #f8f9fd;
    border-color: transparent;
    color: #121212;
  }

  .web-analysis {
    margin-left: 170px;
    margin-right: 150px;
  }

  .webdev {
    margin-left: 170px;
    margin-right: 150px;
  }
</style>
