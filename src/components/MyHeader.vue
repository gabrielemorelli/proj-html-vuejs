<template>
  <header>
    <div class="logo"></div>
    <MenuHeader :items="items" />
    <div class="container">
      <div class="row d-flex align-items-center">
        <div class="col-">
          <h2>Avatar freelancer</h2>
          <h1>Art Director</h1>
          <p>if it doesn't challenge you, it doesnt change you</p>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import MenuHeader from "./partials/MenuHeader.vue";
export default {
  name: "MyHeader",
  props: {
    items: Array,
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
header {
  background-image: url("../assets/img/freelancer_thumbnail.jpg");
  height: 1000px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;

  .title h1 {
    color: #f9245c;
    font-size: 150px;
  }
  .title h2 {
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