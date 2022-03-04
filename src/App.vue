<template>
  <div id="app">
    <HelloWorld />
    <MyHeader :items="items" />
    <MyMain />
    <MyFooter :liste="liste" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    MyHeader,
    MyMain,
    MyFooter
  },
   data() {
    return {
      items: [
        {
          text: "About Me",
         
          section: "a",
        },
        {
          text: "Why Work With Me",
       
          section: "B",
        },
        {
          text: "Recent Work",
        
          section: "C",
        },
        {
          text: "View All Work",
      
          section: "apple",
        },
        {
          text: "Expert Design Advice",
         
          section: "E",
        },
        {
          text: "Let's Work Together",
         
          section: "F",
        },
      ],
        
      liste: [
        {
          text: "Copyright 2012-2020",
        },
        {
          text: "Avada Theme by Theme Fusion",
        },
        {
          text: "All rights reserved",
        },
        {
          text: "Powered by wordpress",
        },
       
      
      ],
      
    

    };
  },
  
     
}
</script>

<style lang="scss">
@import "./style/general.scss";
</style>
