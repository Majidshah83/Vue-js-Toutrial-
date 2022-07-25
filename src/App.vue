<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HeloHome data="Majid shah props" msg="second msg" />
  <OnclickEvents/> -->
  <ForLoop/>
  <!-- <Check/> -->


</template>

<script>
// import HeloHome from './components/HeloHome.vue'
// import OnclickEvents from './components/OnlickEvents.vue'
import ForLoop from './components/ForLoop.vue'
// import Check from './components/Check.vue'
export default {
  name: 'App',
  components: {
  ForLoop,
  // Check
// HeloHome,
//  OnclickEvents    
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
