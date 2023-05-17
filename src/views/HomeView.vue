<template>
  <div class="introduction justify-content center">
    <div class="row">
      <div class="col">
      <h2 class=" mt-5">Hi, I am Buhle Qampi. I am an intern web developer & aspiring AWS Cloud Practioner </h2>
    </div>
    <div class="col mt-5">
      <img src="https://i.postimg.cc/qBFgjvmB/landing-removebg-preview.png" alt="landing"/> 
    </div>
      </div>
      </div>
 </template>
<style scoped>
.introduction {
  color:#F27121;
  font-family: 'TT Ramillas';
}
h2 {
  font-size: 70px;
}

@keyframes bounce{
    from { transform: translate3d(0, 0, 0);}
    to { transform: translate3d(0, 200px, 0);}
}
img{
    animation-name: bounce;
    animation: bounce 0.5s;
    animation-direction: alternate;
    animation-iteration-count: infinite;
}
.col {
  justify-items: left;
}
</style>
