<template>
  <div class="hello">
    <h1> Hello Vue! </h1>
    <p>
      My first Vue.js App!
    </p> <br>
    
    <button id="green">Hover for a surprise!</button>
    <button id="dare" onclick="document.location='https://www.youtube.com/watch?v=DLzxrzFCyOs'">Click if you DARE...</button>
  </div>
 </template>
  
<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h3 {
  margin: 40px 0 0;
}
a {
  color: #bf616a; /*Nord11 - Aurora*/
  text-decoration: none;
}
a:hover {
  color: #ab575f;
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
#green:hover {
  transform: rotate3d(1, 1, 1, 360deg);
  transition-duration: 2s;
}
#dare {
  color: #bf616a; /*Nord11 - Aurora*/
}
</style>
