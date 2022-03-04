<template>
  <main>
    <!--section about-->
    <section id="about">
      <div class="title text-center">
        <h2>About Me</h2>
        <p>ui e ux expert</p>
         <div class="border"></div> 
      </div>
      <div class="container">
        <div class="row">
          <div class="col-6">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab similique nostrum aut sapiente doloremque sit
               non dolorum suscipit quam impedit harum, perspiciatis numquam quasi reiciendis nisi maxime nobis, neque vero.
               Lorem ipsum dolor sit, amet consectetur adipisicing elit.<p>
              <p>Ratione officiis voluptatibus laudantium maxime numquam amet doloribus voluptatem, quo quibusdam sapiente voluptate, 
               vel nesciunt facere eaque. Dignissimos quos quis architecto sit.</p>
          </div>
          <div class="col-6">
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorum corrupti molestiae eligendi officiis doloremque ipsa nihil at dolorem deleniti et sunt nobis,
               obcaecati perspiciatis fugit asperiores delectus praesentium autem id.</p>
               <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quo accusantium est, ipsam amet delectus inventore placeat possimus corporis autem voluptates aliquam deleniti deserunt harum iste dolore assumenda quidem. 
                 Qui, harum.</p>
          </div>
        </div>
      </div>
    </section>
<!--fine section about-->

<!--inizio section work-->
<section id="work">
  <div class="title text-center">
    <h2>Why Work With Me</h2>
    <p>web.Branding.ux/ui</p>
     <div class="border"></div> 
  </div>
<div class="container">
  <div class="row text-center">
    <div class="col-12">
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora excepturi doloremque mollitia molestiae, voluptate dignissimos ipsam.
         Laborum esse amet voluptates excepturi nesciunt doloribus temporibus explicabo rerum veniam! Ab, placeat sapiente.</p>
    </div>
  </div>
  <div class="row text-center">
    <div class="col-4">
      ciao
    </div>
    <div class="col-4">
      ciao
    </div>
    <div class="col-4">
      ciao
    </div>
  </div>
</div>
<div class="container">
<div class="row text-white">
  <div class="col-4">
    ciao
  </div>
   <div class="col-4">
    ciao
  </div>
   <div class="col-4">
    ciao
  </div>
</div>

</div>
</section>
<!--fine section work-->
<!--inizio section recent work-->
<section id="recent-work">
  <div class="title text-center text-white">
    <h2>Recent Work</h2>
    <p>Web.Branding.ux/ui</p>
    <div class="border"></div> 
  </div>

<div class="container-fluid">
  <div class="row">
    <div class="col-6">
   <img src="../assets/img/portfolio1_featured_item.jpg" class="img-fluid">
    </div>
    <div class="col-6">
   <img src="../assets/img/portfolio1_featured_item.jpg" class="img-fluid">
    </div>
  </div>
 </div>
  </section>
 <!--fine  section recent work-->
 <section id="view">
   <div class="title text-center text-white text-uppercase">
     <p>View all work</p>
   </div>
 </section>
 <section id="apple">
   <div class="title text-center">
     <div class="apostrofo">

     </div>
     <p></p>
     <h4>Steve Jobs-Apple</h4>
   </div>
   <div class="container">
     <div class="title text-center">
       <h4>Trusted by global brands</h4>
     </div>
     <div class="row d-flex justify-content-center">
       <div class="col-2">
        <img src="../assets/img/Vector_Smart_Object-1.png" class="img-fluid">
        
       </div>
       <div class="col-2">
        <img src="../assets/img/Vector_Smart_Object-1.png">
       </div>
       <div class="col-2">
        <img src="../assets/img/Vector_Smart_Object-1.png">
       </div>
       <div class="col-2">
         <img src="../assets/img/Vector_Smart_Object-1.png">
       </div>
       <div class="col-2">
         <img src="../assets/img/Vector_Smart_Object-1.png">
       </div>

     </div>
   </div>
 </section>
  </main>
</template>

<script>
export default {
name: "MyMain"
}
</script>

<style>

/*section about*/
#about{
  background-color: #20232c;
  }

.title{
  padding: 50px;
}

#about .row p {
  color:#2d5793;
  
}

.border{
  border: 1px solid white;
  width: 70px;
  text-align: center;
  
}

#about .title h2{
 color: white;
}

#about .title p {
  color: #2d5793;
  text-transform: uppercase;
  
}

/*section work*/
#work{
  background-color: #191c23;
}


#work .title h2{
 color: white;
}

#work .title p {
  color: #2d5793;
  text-transform: uppercase;
  
}

#work .row p {
  color:#2d5793;
  
}

/*section recent work*/
#recent-work{
  background-color: #96c577;
}

/*section viee*/
#view{
  background-color:#f9225b ;
}

</style>