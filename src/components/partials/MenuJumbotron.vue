<template>
  <div>
        <section id="jumbotron">
  
        <div class="container">
          <div class="row align-middle">
            <div class="col  text-center">
              <h2>Avatar freelancer</h2>
              <h1>Art Director</h1>
              <p>if it doesn't challenge you, it doesnt change you</p>
            </div>
          </div>
        </div>

        

    </section> 
  </div>
</template>

<script>

export default {
name:"MenuJumbotron"
}
</script>

<style scoped lange="scss">

#jumbotron{
  background-image: url("../../assets/img/freelancer_thumbnail.jpg");
  height: 100vh;
  width: 100%;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  
}

#jumbotron .container{
  height: 100%;
  width: 100%;
}

.row h1 {
  color: #f9245c;
  font-size: 150px;
}
.row h2 {
  color: white;
  font-size: 50px;
}
.row p {
  color: grey;
  font-size: 30px;
 
}

</style>