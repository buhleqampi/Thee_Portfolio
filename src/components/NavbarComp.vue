<template>
<nav class="navbar navbar-expand-md"> 
<ul>
<li style="display:inline" class="logo">
<img src="https://i.postimg.cc/HkZM7fBz/logo2.png" alt="logo"/>
</li>
<li style="display:inline" id="bar">
<router-link to="/">Home</router-link> 
</li>
<li style="display:inline">
<router-link to="/about">About</router-link> 
</li>
<li style="display:inline">
<router-link to="/resume">Resume</router-link> 
</li>
<li style="display:inline">
<router-link to="/projects">Projects</router-link>
</li>
<li style="display:inline">
<router-link to="/testimonials">Testimonials</router-link> 
</li> 
<li style="display:inline">
<router-link to="/contact">Contact</router-link>  
</li>
</ul>
<hr>   
</nav>
</template>

<style scoped>
nav ul li {
   font-family: Arial, Helvetica, sans-serif;
}
   li {
      padding:10px;
   }
   ul li a{
      text-decoration: none;
      color:whitesmoke;
   }
   #bar {
      font-family: Arial, Helvetica, sans-serif;
   }
   img{
      width:100px;
   }
</style>
