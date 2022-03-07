<template>
  <div>
    <div class="container">
      <div class="row">
        <div class="col offset-2">
          <ul>
            <li v-for="(lista, index) in liste" :key="index">
              
               <a href="`{lista.url}`"> {{lista.text}}</a>
          </li>
            </ul>
          </div>    
      </div>
    </div>

  <div class="container pb-5">
      <div class="row">
        <div class="col offset-5">
         <ul>
           <li  v-for="(social, index) in socials" :key="index">
           <a href="`{social.url}`"><i :class="social.icon"></i> </a>            
          </li>
         </ul>         
        </div>
      </div> 
    </div>
    
  
  </div>
</template>

<script>
export default {
  name: "MenuFooter",
  props: {
    liste: Object,
    socials: Object,
  },
};
</script>

<style>


.container ul {
list-style: none;
}

.container li{
  display: inline;
  padding: 10px;
  color:#72697a ;
  
}

 footer .container i{
  background-color: white;
  padding: 10px;
  font-size: 20px;
}

footer .container a{
  text-decoration: none;
  color:#72697a;
}
</style>

