<template>
  <div>
    <div class="container">
   <div class="row ms_mb text-center">
     <div class="col-8 offset-2">
       <div class="row row-cols-4 ">
           <div class="col" v-for="(lista, index) in liste" :key="index">
            {{ lista.text }}
            {{ lista.social }}
          </div>
       </div>
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
  },
};
</script>

<style>
.ms_mb{
  margin-bottom: 100px;
}


</style>

