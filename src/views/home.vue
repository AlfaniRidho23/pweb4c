<template>
    <!--banner image-->
  
    <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
      <div  class="images">
        <div class="profile">
        <img src="https://png.pngtree.com/png-vector/20200921/ourlarge/pngtree-red-and-black-logo-png-image_2348180.jpg" class="rounded-circle"
             height="300px" width="300px">
      </div>
      <div class="content text-center">
        <h1 class="text-white">M. Ridho Alfani</h1>
        <h2>Selamat Datang Di website Saya</h2>
      </div>
      </div>
    </div>
  
  
  </template>
  
  <script>
  export default {
    name: 'App',
    components: {
      // HelloWorld
    }
  }
  </script>
  
  <style>
  .text-center{
    margin-top: 50px;
  }
  .images {
    margin-top: -100px;
  }
  .banner-image{
    background: #4c49f9;
    background-size: cover;
  }
  
  
  </style>
  