<template>
  <body>
  <div class="introduction justify-content center">
    <div class="row" style="display: flex; align-items: center;">
      <div class="col">
      <h2 class=" mt-5"  >Hi, I am Buhle Qampi.
      I am an intern web developer & aspiring AWS Cloud Practitioner </h2>
      <ul class="icons" >
            <li style="display: inline;">
                <a href="https://github.com/" target="_blank"><i class="fa-brands fa-github fa-5x"></i></a>
            </li>
            <li style="display:inline">
                <a href="https://www.linkedin.com/in/buhle-qampi-293140158/" target="_blank"><i class="fa-brands fa-linkedin fa-5x"></i></a>
            </li>
        </ul>   
    </div>
    <div class="col mt-5">
      <img src="https://i.postimg.cc/qBFgjvmB/landing-removebg-preview.png" alt="landing"/> 
    </div>
      </div>
      </div>
    </body>
 </template>
<style scoped>
.introduction {
  color:#F27121;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
h2 {
  font-size: 65px;
}
body{
  min-height: 100vh;
  background-color: #1f1f1f;
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
}
.col {
  justify-items: left;
}
ul li {
    padding:15px;
}
ul li a {
    color:gray;
}
.col ul li a:hover i {
  color: #ffffff;
}
.icons li a i:hover {
  animation: bounce 0.5s;
}

@keyframes bounce {
  0%,
  100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.2);
  }
}
@media screen and (max-width:576px) {
  h2 {
  font-size: 60px;
  line-height:3.5rem;
}
img{
  margin-bottom:45px;
}

}
</style>
