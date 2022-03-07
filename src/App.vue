<template>
  <div id="app">
    <HelloWorld />
    <MyHeader :items="items" />
    <MyMain />
    <MyFooter :liste="liste" :socials="socials"  />
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
         
          section: "#aboutme",
        },
        {
          text: "Why Work With Me",
       
          section: "#work",
        },
        {
          text: "Recent Work",
        
          section: "#recent",
        },
        {
          text: "View All Work",
      
          section: "#apple",
        },
        {
          text: "Expert Design Advice",
         
          section: "#E",
        },
        {
          text: "Let's Work Together",
         
          section: "#F",
        },
      ],
        
      liste: [
        {
          text: "Copyright 2012-2020 |",
          url: "#",
        },
        {
          text: "Avada Theme by Theme Fusion |",
              url: "#",
        },
        {
          text: "All rights reserved |",
              url: "#",
        },
        {
          text: "Powered by wordpress",
              url: "#",
        },
       
      
      ],

      socials: [
           {
          icon: "fa-brands fa-facebook",
          url: "#"
        },
        {
          icon: "fa-brands fa-twitter",
           url: "#"
        },
        {
          icon: "fa-brands fa-youtube",
           url: "#"
        },
        {
          icon: "fa-brands fa-instagram",
           url: "#"
        },
      ]
      
    

    };
  },
  
     
}
</script>

<style lang="scss">
@import "./style/general.scss";
</style>
