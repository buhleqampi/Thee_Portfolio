<template>
    
<section class="design-section">
    <h1 class="text-white">RESUME</h1>
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
      <h2 class="tech">TECH STACK</h2>
       <div class="col">
       <i class="fa-brands fa-html5"></i>
       <i class="fa-brands fa-css3-alt"></i>
       <i class="fa-brands fa-square-js"></i>
       <i class="fa-brands fa-node-js"></i>
       <i class="fa-brands fa-vuejs"></i>
       <i class="fa-brands fa-bootstrap"></i>
       <i class="fa-brands fa-figma"></i>
       <i class="fa-brands fa-wordpress"></i>
       <i class="fa-brands fa-microsoft"></i>
      </div>
</section>

</template>
<style>
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

.design {
  display: flex;
  align-items: center;
  justify-content: center;
}

.timeline {
  width: 80%;
  height: auto;
  max-width: 800px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}

.timeline-content {
  padding: 20px;
  background: #1f1f1f;
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
}

@media screen and (min-width: 768px) {
  .timeline {
    display: grid;
    grid-template-columns: 1fr 3px 1fr;
  }
  .timeline-middle {
    position: relative;
    background-image: linear-gradient(45deg, #F27121, #E94057, #8A2387);
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
    background-image: linear-gradient(45deg, #F27121, #E94057, #8A2387);
    -webkit-transform: translateX(-50%);
            transform: translateX(-50%);
  }
  .tech{
    color: white;
    margin-top: 15px;
  }
}</style>