<template>
  <div id="app">
        <HelloWorld />
        <MyHeader />
        <MyMain />
        <MyFooter />
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
  }
}
</script>

<style lang="scss">

</style>
