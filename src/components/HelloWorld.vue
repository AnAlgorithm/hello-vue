<template>
  <div class="hello">
  
    <h1>Hello Vue!</h1>
    
    <p>
      My first Vue.js App!
    </p>
    
    <br>
    
    <button id="green" onclick="startConfetti()">Click for a surprise!</button>
    <button id="red">Click if you DARE...</button>
    
    <script>
    const btn = document.getElementById("red");

btn.addEventListener("click", ()=>{

    if(btn.value === "Click if you DARE..."){
        btn.value = "Nothing Happened!";
    } else{
        btn.value= "Click if you DARE...";
    }
})
   </script> 
  </div>
 </template>
  
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

button {
  background-color: #0a0a0a;
  padding: 8px;
  margin: 40px;
  border: 1px solid #f2f2f2;
  border-radius: 5px;
  font-size: 18px;
  cursor: pointer;
}

button:hover {
  background-color: #121212;
}

#green {
  color: #42b983;
}

#red {
  color: #bf616a; /*Nord11 - Aurora*/
}

</style>
