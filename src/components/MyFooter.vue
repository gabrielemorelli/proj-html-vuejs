<template>
  <footer>
    <div class="title text-center">
      <img src="../assets/img/avada-freelance-logo.png" alt="">
    </div>
   
      <MenuFooter :liste="liste" />
       
     
   
  </footer>
</template>

<script>
import MenuFooter from "./partials/MenuFooter.vue";
export default {
  name: "MyFooter",
  props: {
 liste: Array,
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
  background-color: aqua;
height: 200px;
}
</style>