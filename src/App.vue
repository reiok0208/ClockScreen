<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg2="HelloWorld"/> -->
  <Clock />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import HelloWorld from './components/NewPage.vue'
import Clock from './components/ClockScreen.vue'

export default {
  name: 'App',
  components: {
    Clock,
  }
}
</script>

<style>
  html,
  body {
    height: 100%;
    margin: unset;
  }
  #app {
    height: 100%;
  }
  </style>
