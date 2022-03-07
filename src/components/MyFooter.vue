<template>
  <footer>
    <div class="title text-center">
      <img src="../assets/img/avada-freelance-logo.png" alt="">
    </div>
   
      <MenuFooter :liste="liste" :socials="socials" />
       

     
   
  </footer>
</template>

<script>
import MenuFooter from "./partials/MenuFooter.vue";
export default {
  name: "MyFooter",
  props: {
 liste: [],
 socials: []
  },
 
  components: {
    MenuFooter,
  },
  data() {
    return {};
  },
};
</script>

<style>
footer{
  background-color: black;

}

footer .title{
  padding: 30px;
}
</style>