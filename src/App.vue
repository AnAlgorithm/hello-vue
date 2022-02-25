<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}


const btn = document.getElementById("red");
btn.addEventListener("click", ()=>{

    if(btn.value === "Click if you DARE..."){
        btn.value = "Nothing Happened!";
    } else{
        btn.value= "Click if you DARE...";
    }
})

</script>

<style>
body {
  background-color: #2c3e50; /*Nord0 - Polar Night*/
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #eceff4; /*Nord6 - Snow Storm*/
  margin-top: 60px;
}
</style>
