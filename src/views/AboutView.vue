<template>
  <body>
      <div class="container px-5">
    <div class="row" style="height: 100%;">
  <h1 class="d-flex justify-content-center mt-2 text-white">About Me</h1> 
  <div class="row d-flex flex-column flex-sm-row justify-content-center">
    <div class="col">
      <img src="https://i.postimg.cc/3J3jBGzN/My-project.jpg" alt="picture"/>
    </div>
    <div class="col">
      <p class="lead text-white">My name is <strong>Buhle Qampi</strong>,and I was born on the 14th of August 2000.
        My hobbies include watching documentaries about the innovation of Artificial Intelligence and new inventions of frameworks to JavaScript.
        I am an intern developer in the field of full-stack.I am a winner and know that with programming you do not always win, bugs and errors always try to complicate your code, 
        but nothing is of greater satisfaction when you debug and fix your code, no matter how long after how you struggled.I am a goal-driven, a team player and attentive to detail when it comes to design beautiful and professional websites.</p></div>
  </div>
  </div>
  </div>
</body>
</template>

<style scoped>
 body{
  min-height: 100vh;
  background-color: #1f1f1f;
 }
h1{
  font-family: Arial, Helvetica, sans-serif;
 }
img{
  width:500px;
  margin-bottom:5px;
}
.lead {
  margin-bottom:20px;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 25px;
 }
 
 @media screen and (max-width: 992px) {
  img{
  width:500px;
}
.lead {
  display: inline;
  font-size: 19px;
 }
 body{
  min-height: 100vh;
  background-color: #1f1f1f;
 }
 }
</style>
