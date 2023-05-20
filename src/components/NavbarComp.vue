<template>
     <div>
            <nav class="navbar navbar-expand-lg sticky">
                <div class="container-fluid">
                    <div class="logo">
                        <img src="https://i.postimg.cc/HkZM7fBz/logo2.png"/>
                    </div>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                     <li style="display:inline" id="bar">
                        <router-link to="/" class="active">Home</router-link> 
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
                </div>
                </div>
            </nav>
        </div>
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
      color:gray;
   }
   #bar {
      font-family: Arial, Helvetica, sans-serif;
   }
   img{
      width:100px;
   }
   #bar {
      flex-direction: column;
   }
   nav ul li:hover {
  background-color: #ffffff; 
  color: #000000; 
}
</style>
