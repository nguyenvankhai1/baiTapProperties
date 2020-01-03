<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <hienThi/> -->
    <!-- <VongDoi/> -->
    <baiTapProperties postTitle='GIÁ TRỊ'></baiTapProperties>


  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// import hienThi from './components/hienThi'

// import VongDoi from './components/VongDoi'

import baiTapProperties from'./components/baiTapProperties'

export default {
  name: 'app',
  components: {
    // HelloWorld
    // hienThi
    // VongDoi
    baiTapProperties
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
