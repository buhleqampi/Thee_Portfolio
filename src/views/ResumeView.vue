<template>
  <h1 class="d-flex justify-content-center mt-2 text-white">Resume</h1>
  <section class="design-section"> 
  <div class="timeline">
    <div class="timeline-empty">
                  </div>
                  <div class="timeline-middle">
                   <div class="timeline-circle"></div>
               </div>
               <div class="timeline-component timeline-content">
                <h4>LC Studio</h4>
                <p>Intern Web developer</p>
                <p>April 2023- Currently</p>
           </div>
                <div class="timeline-component timeline-content">
                         <h4>Life Choices Academy</h4>
                         <p>Student</p>
                         <p>Sept 2022- Mar 2023</p>
                </div>
                <div class="timeline-middle">
                    <div class="timeline-circle"></div>
                </div>
                <div class="timeline-empty">
                </div>

                <div class="timeline-empty">
                </div>

               <div class="timeline-middle">
                   <div class="timeline-circle"></div>
               </div>
               <div class=" timeline-component timeline-content">
                <h4>IkamvaYouth</h4>
                <p>High School Programme Admin</p>
                <p>Sept 2022- Nov 2022</p>
           </div>

       </div>
       <div class="container text-center">
      <h1 class="tech">Tech Stack</h1>
       <div class="row">
       <div class="col"><i class="fa-brands fa-html5 fa-6x fade-in"></i></div>
       <div class="col"><i class="fa-brands fa-css3-alt fa-6x fade-in"></i></div>
        <div class="col"><i class="fa-brands fa-square-js fa-6x fade-in"></i></div>
        <div class="col"><i class="fa-brands fa-node-js fa-6x fade-in"></i></div>
        </div>
        <div class="row">
        <div class="col"><i class="fa-brands fa-vuejs fa-6x fade-in"></i></div>
        <div class="col"><i class="fa-brands fa-bootstrap fa-6x fade-in"></i></div>
        <div class="col"><i class="fa-brands fa-figma fa-6x fade-in"></i></div>
        <div class="col"><i class="fa-brands fa-wordpress fa-6x fade-in"></i></div>
        </div>
        <div class="row">
          <div class="col">
            <a href="https://drive.google.com/file/d/1LwfZj0rjS4WY99Scb3zm0U6NOQH-_Cc3/view?usp=sharing" target="_blank" ><button type="button" class="btn btn-secondary btn-lg">Download CV</button></a>
          </div>
          <div class="col">
            <a href="https://drive.google.com/file/d/17OEbUJNDyfMeEOeo1KuIwAzgWNN8I3G-/view?usp=sharing" target="_blank" ><button type="button" class="btn btn-secondary btn-lg">Download Certificate</button></a>
          </div>
          </div>
      </div>
</section>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Jost:wght@200;300;400&display=swap');
.design-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color: #1f1f1f;
  min-height: 100vh;
  padding: 100px 0;
  /* font-family: Old Standard TT; */
}
.timeline {
  width: 50%;
  height: auto;
  max-width: 800px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}
.timeline-content {
  padding: 20px;
  background: #F27121;
  -webkit-box-shadow: 5px 5px 10px #1a1a1a, -5px -5px 10px #242424;
          box-shadow: 5px 5px 10px #1a1a1a, -5px -5px 10px #242424;
  border-radius: 5px;
  color: white;
  /* padding: 1.75rem; */
  transition: 0.4s ease;
  overflow-wrap: break-word !important;
  margin: 1rem;
  margin-bottom: 20px;
  /* border-radius: 6px; */
}
.timeline-component {
  margin: 0px 20px 20px 20px;
  font-family: Georgia, 'Times New Roman', Times, serif
}

@media screen and (min-width: 768px) {
  .timeline {
    display: grid;
    grid-template-columns: 1fr 3px 1fr;
  }
  .timeline-middle {
    position: relative;
    background-image: linear-gradient(45deg,whitesmoke , #454545);
    width: 3px;
    height: 100%;
  }
  .main-middle {
    opacity: 0;
  }
  .timeline-circle {
    position: absolute;
    top: 0;
    left: 50%;
    width: 15px;
    height: 15px;
    border-radius: 50%;
    background-image: linear-gradient(45deg,whitesmoke, #454545);
    -webkit-transform: translateX(-50%);
            transform: translateX(-50%);
  }
}
tech{
    color: white;
    margin-top: 25px;
  }
  .col{
    color:#F27121;
  }
h1 {
  font-family: Arial, Helvetica, sans-serif;
}
.btn {
        font-family: Georgia, 'Times New Roman', Times, serif;
        background-color:#025464;
    }
    .fade-in {
  opacity: 1;
  transition: opacity 0.3s ease;
}

.fade-in:hover {
  opacity: 0.5;
}

</style>