<template>
    <div class="container px-5">
        <div class="row" style="height: 100%;">
            <h1 class="d-flex justify-content-center mt-2 text-white">Testimonials</h1>
    <figure class="lebo">
  <figcaption>
    <blockquote>Buhle is a sweet and loving soul. She is a hard worker and once she puts her mind to something she get it done.</blockquote>
    <div class="arrow"></div>
  </figcaption>
  <img src="https://i.postimg.cc/QM2QdyjC/C11-Kelebogile-Nobomvu-4.jpg" alt="sq-sample10"/>
  <div class="author">
    <h5>Kelebogile Nobomvu<span>- Collegue</span></h5>
  </div>
 </figure>
<figure class="lebo hover">
  <figcaption>
    <blockquote>Buhle is one that you can easily approach, she's always willing to assist anyone.She is a respectful individual and I enjoy engaging with her.</blockquote>
    <div class="arrow"></div>
  </figcaption>
  <img src="https://i.postimg.cc/brsRrRfP/C3.jpg" alt="sq-sample33"/>
  <div class="author">
    <h5>Chrisaner Matthys<span>- Collegue</span></h5>
  </div>
</figure>
<figure class="lebo hover">
  <figcaption>
    <blockquote>Buhle is a very kind hearted person.She believes in being a positive role model to those who look up to her. A key value she holds dear is Respect."</blockquote>
    <div class="arrow"></div>
  </figcaption>
  <img src="https://i.postimg.cc/7Y8H2hvY/Candice.jpg" alt="sq-sample33"/>
  <div class="author">
    <h5>Candice Amon<span>- Facilitator</span></h5>
  </div>
</figure>
<figure class="lebo hover">
  <figcaption>
    <blockquote>Buhle is a dedicated individual who puts her all in her work and a good team player, good at planning and meeting deadlines.</blockquote>
  </figcaption>
  <img src="https://i.postimg.cc/52Tffw2b/Siba1.jpg" alt="sq-sample33"/>
  <div class="author">
    <h5>Sibabalwe Mafestire<span>- Collegue</span></h5>
  </div>
</figure>
    </div>
    </div>
</template>

<style scoped>
@import url(https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css);
@import url(https://fonts.googleapis.com/css?family=Raleway:400,800);
figure.lebo {
  font-family: 'Raleway', Arial, sans-serif;
  position: relative;
  margin: 40px;
  min-width: 400px;
  max-width: 480px;
  width: 100%;
  color: #333;
  text-align: left;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.15);
  background-color:#025464;
  border-radius: 8px 8px 8px 8px;
}
figure.lebo * {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}
figure.lebo img {
  float: right;
  width:100%;
  height:100%;
  max-width: 30%;
  vertical-align: middle;
  border-radius:50% 50% 50% 50%;
 
}
figure.lebo figcaption {
  top: 0;
  bottom: 0;
  left: 0;
  width: 60%;
  position: absolute;
  background-color: #ffffff;
  border-radius: 8px 0 0 8px;
}
figure.lebo blockquote {
  position: relative;
  padding: 25px 50px 25px 50px;
  font-size: 0.8em;
  font-weight: 500;
  text-align: left;
  margin: 0;
  line-height: 1.6em;
  font-family: Georgia, 'Times New Roman', Times, serif;
}
figure.lebo blockquote:before,
figure.lebo blockquote:after {
  font-family: 'FontAwesome';
  content: "\201C";
  position: absolute;
  font-size: 50px;
  opacity: 0.3;
  font-style: normal;
}
figure.lebo blockquote:before {
  top: 25px;
  left: 20px;
}
figure.lebo blockquote:after {
  content: "\201D";
  right: 20px;
  bottom: 0px;
}
figure.lebo .arrow {
  top: 30px;
  left: 100%;
  width: 0;
  height: 0;
  border-left: 0 solid transparent;
  border-right: 25px solid transparent;
  border-top: 25px solid #ffffff;
  margin: 0;
  position: absolute;
}
figure.lebo .author {
  position: absolute;
  top: 100%;
  width: 60%;
  padding: 10px 15px;
  color: #ffffff;
  margin: 0;
  text-transform: uppercase;
}
figure.lebo .author h5 {
  opacity: 0.8;
  margin: 0;
  font-weight: 800;
}
figure.lebo .author h5 span {
  font-weight: 400;
  text-transform: none;
  padding-left: 5px;
}
h1{
  font-family: Arial, Helvetica, sans-serif;
}
</style>
