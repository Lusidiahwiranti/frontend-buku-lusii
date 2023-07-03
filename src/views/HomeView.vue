<template>
  <!--banner image-->

  <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
    <div class="content text-center">
      <h1 class="text-white">WELCOME TO XUXI'S LIBRARY!</h1>
    </div>
    <div class = "col-lg-4">
      <img src="../assets/buku.jpg" class="img-fluid">
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
.banner-image{
  background: #bc968f;
  font-family: "Times New Roman" ;
  font-style: italic;
  font-size: 30px;
}
.col-lg-4{
 margin-left: 20px;
}

</style>