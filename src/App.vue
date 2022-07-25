<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HeloHome data="Majid shah props" msg="second msg" />
  <OnclickEvents/>

</template>

<script>
import HeloHome from './components/HeloHome.vue'
import OnclickEvents from './components/OnlickEvents.vue'
export default {
  name: 'App',
  components: {

HeloHome,
OnclickEvents    
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
