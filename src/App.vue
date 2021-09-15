<template>
  <img alt="Ace-t logo" src="./assets/acet.png">
  <my-component></my-component>
  <VuePlay msg="vue.js로 이것저것 해보아요!"/>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import VuePlay from './components/VuePlay.vue'
//
// var MyComponent = {
//   template: '<p class="vue-play">Hello</p>'
// }
export default {
  name: 'App',

  components: {
    VuePlay
    // 'my-component': MyComponent
  }

}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
