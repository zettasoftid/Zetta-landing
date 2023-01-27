<template>
  <div class="container my-5">
    <div class="text">You can see our media:</div>
    <img src="../assets/svg/Github.svg" alt="github zetta" />
    <img src="../assets/svg/Instagram.svg" alt="instagram zetta" />
    <img src="../assets/svg/LinkedIn.svg" alt="instagram zetta" />
    <img src="../assets/svg/Medium.svg" alt="instagram zetta" />
    <img src="../assets/svg/YouTube.svg" alt="instagram zetta" /> />
  </div>
</template>

<script>
  export default {
    name: "Sosmed",
  };
</script>

<style>
  .container {
    border-radius: 8px;
    padding: 24px;
    background-color: #333;
    display: flex;
    align-items: center; /* mengatur posisi rata tengah secara vertikal */
  }

  .text {
    font-size: 34px;
    font-weight: 500;
    color: #fff;
    margin-left: 10px;
    margin-right: auto; /* menempatkan elemen teks ke sisi kiri */
  }

  img {
    margin-right: 20px;
    margin-left: 20px; /* menempatkan elemen gambar ke sisi kanan */
  }
</style>
