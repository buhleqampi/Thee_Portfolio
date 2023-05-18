<template>
  <div class="introduction justify-content center">
    <div class="row">
      <div class="col">
      <h2 class=" mt-5"  style="display: flex; align-items: center;">Hi, I am Buhle Qampi.
      I am an intern web developer & aspiring AWS Cloud Practioner </h2>
    </div>
    <div class="col mt-5">
      <img src="https://i.postimg.cc/qBFgjvmB/landing-removebg-preview.png" alt="landing"/> 
    </div>
    <div class="row">
            <ul class="icons" style="text-align: left;">
            <li style="display: inline;">
                <a href="https://github.com/" target="_blank"><i class="fa-brands fa-github fa-5x"></i></a>
            </li>
            <li style="display:inline">
                <a href="https://www.linkedin.com/in/buhle-qampi-293140158/" target="_blank"><i class="fa-brands fa-linkedin fa-5x"></i></a>
            </li>
        </ul>   
        </div>
      </div>
      </div>
 </template>
<style scoped>
.introduction {
  color:#F27121;
  font-family: Arial, Helvetica, sans-serif;
}
h2 {
  font-size: 65px;
}

@keyframes orbit{
   0%{
    transform:rotate(0deg);
   }
   100%{
    transform:rotate(360deg);
   }
}
img{
    animation-name: bounce;
    animation: orbit 10s linear infinite;
    /* animation-direction: linear;
    animation-iteration-count: infinite; */
}
.col {
  justify-items: left;
}
ul li {
    padding:15px;
}
</style>
