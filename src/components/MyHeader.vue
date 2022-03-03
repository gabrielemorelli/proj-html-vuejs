<template>
  <header>
    <div class="container-fluid">
      <div class="logo">
        <div>immagine</div>
      </div>
      <div class="d-flex justify-content-end">ciao</div>
    </div>
    <div class="title text-center">
        <h2>Avatar frellencer</h2>
        <h1>Art Directro</h1>
        <p>if it doesn't challenge you, it doesnt change you</p>
        
    </div>
  </header>
</template>

<script>
export default {
  name: "MyHeader",
};
</script>

<style  scoped lang="scss">

header {
    background-image: url("../assets/img/freelancer_thumbnail.jpg");
    height: 1000px;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
   
   .title h1{
       color: #f9245c;
       font-size: 150px;
   }
   .title h2{
       color: white;
       font-size: 50px;
   }
   .title p {
       color: grey;
       font-size: 30px;
       text-transform: uppercase;
   }
}
</style>