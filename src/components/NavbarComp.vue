<template>
<nav class="navbar navbar-expand-sm"> 
<ul>
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
 li {
    padding:10px;
 }
 ul li a{
    text-decoration: none;
    color:black;
 }
 #bar {
    font-family: Arial, Helvetica, sans-serif;
 }
</style>
