<template>
  <header>
    <div class="logo"></div>
    <MenuHeader :items="items" />
   
  </header>
</template>

<script>
import MenuHeader from "./partials/MenuHeader.vue";
export default {
  name: "MyHeader",
  props: {
    items:[] ,
   
  },
  components: {
    MenuHeader,
  },
  data() {
    return {};
  },
};
</script>

<style  scoped lang="scss">

header{
  position:fixed;
  width: 100%;
  opacity: 0.6;
 }




</style>