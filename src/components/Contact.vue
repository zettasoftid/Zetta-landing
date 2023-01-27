<template>
  <div class="container-xxl my-5">
    <div class="row">
      <div class="contact">
        <div class="col-lg-5 contact-left">
          <img src="../assets/foto/Contact.png" alt="contact" />
        </div>
        <div class="col-lg-7 contact-right">
          <h3>Our Teams</h3>
          <p>
            A website that serves services in the form of Development <br />
            to Web Scraping services
          </p>
          <a
            href="https://api.whatsapp.com/send?phone=6285156012600"
            class="btn btn-contact"
            >Hire us!</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Contact",
  };
</script>

<style>
  .contact {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .contact-left {
    margin-right: 40px;
  }
  .contact-left img {
    height: 450px;
    widows: 450px;
  }

  .contact-right h3 {
    font-size: 34px;
    font-weight: 500;
    color: #fff;
  }
  .contact-right p {
    margin-top: 10px;
    font-size: 20px;
    font-weight: 500;
    color: #b3b3b3;
  }
  .btn-contact {
    margin-top: 30px;
    font-size: 20px;
    font-weight: 600;
    padding: 10 16 10 16;
    background-color: #f8f9fd;
    color: #121212;
  }
  .btn-contact:hover {
    margin-top: 30px;
    font-size: 20px;
    font-weight: 600;
    padding: 10 16 10 16;
    background-color: #f8f9fd;
    color: #121212;
  }
</style>
