<template>
<div>
    <h1 class="asu">ASU CONFIGURATOR</h1>
    
    <router-link :to="{ name: 'Form'}" class="btn"><b>Create Project</b></router-link>
    <!-- <button class="btn"><b>Create Project</b></button> -->
    <button class="btn"><b>Edit Project</b></button>
    <button class="btn"><b>List of All Project</b></button>
    
</div>
</template>

<script lang="ts">

export default {
  name: 'Admin'
}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
} 
.btn,
button {
  display: inline-block; 
  background:white; 
  color: white;
  text-decoration: none;
  padding: 10px 20px;
  cursor: pointer;
  border-radius: 10px;
  margin-bottom: 15px;
  text-align: center;
  border: none;
   font-size: 30px;
  margin-left: 250px;
  margin-right: auto;
  padding: 80px;
   box-shadow: 10px 2px 15px rgba(0, 0, 0, 0.1);
  cursor: pointer;
  outline: none;
   color: black;
    background-size: cover; 
  /* padding-left: 70px; */
   /* padding-right: 70px; */
}

.asu{
   text-align: center;
   font-size: 70px;
   margin: 100px;
}

.body{
      background-color: #f4f4f4;
}

 body {
    margin: 0;
    padding: 0; 
    background-size: cover; 

    font-family: 'Open Sans', Arial, Helvetica, sans-serif;
    font-size: 16px;
    line-height: 1.5em;
    background-color: #f4f4f4;
    color: #5a5656;
    background-repeat: no-repeat;
} 
*{

    margin: 3px 0px 0px 0px;
    padding: 0px; 
    box-sizing: border-box;
    }
    
</style>


