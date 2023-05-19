<template>
        <div class="row">
        <div class="col">
        <h2 class="d-flex justify-content-center mt-2 text-white">Connect with me</h2>
        <div class="row">
            <p class="larger-p"><i class="fa-solid fa-location-dot"></i>Nyanga, Cape Town</p>
            <p class="larger-p"><i class="fa-solid fa-phone"></i>0636350263</p>
            <p class="larger-p"><i class="fa-solid fa-envelope"></i>buhle3857@gmail.com</p>
        </div>
        <div class="row">
            <ul class="icons">
            <li>
                <a href="https://github.com/" target="_blank"><i class="fa-brands fa-github fa-3x"></i></a>
            </li>
            <li>
                <a href="https://www.linkedin.com/in/buhle-qampi-293140158/" target="_blank"><i class="fa-brands fa-linkedin fa-3x"></i></a>
            </li>
            <li>
                <a href="https://www.facebook.com/buhle.qampi/" target="_blank"><i class="fa-brands fa-facebook fa-3x "></i></a>
            </li>
            <li>
                <a href="https://www.instagram.com/gingerqamps/"  target="_blank"><i class="fa-brands fa-instagram fa-3x"></i></a>
            </li>
        </ul>   
        </div>
     </div>
        <div class="col">
        <h2 class="d-flex justify-content-center mt-2 text-white">Get In Touch!</h2>
        <form action ="https://formspree.io/f/mwkjydzb" method="POST">
        <div class="mb-3 ">
            <label for="first" class="form-label">First name</label>
            <input type="first" name="first" class="form-control" id="example" required>
        </div>
        <div class="mb-3">
            <label for="last" class="form-label">Last Name</label>
            <input type="last" name="last" class="form-control" id="example"  required>
        </div>
        <div class="mb-3">
            <label for="subject" class="form-label">Subject</label>
            <input type="subject" name="subject" class="form-control" id="example" required>
        </div>
        <label for="message" class="form-label">Message</label>
        <textarea type="message" name="message" class="form-control" id="exampleInputMessage" placeholder="Write something" required></textarea>
        <button type="submit" class="btn btn-secondary submit-btn" style="margin-top: 10px;">Submit</button>
        </form>
        </div>
        </div>
    </template>

<style scoped>
form {
    margin:5px;
}
ul li a {
    color:gray;
    width:200px;
}
h2{
    font-family: Arial, Helvetica, sans-serif;
}
ul li {
    padding:10px;
}
.row i {
        padding-right: 5px;
    }
.submit-btn{
    background-color:  #025464;
} 
.larger-p {
    font-size: 2rem; 
}
.icons li a i {
  transition: transform 0.3s; 
}

/* Add bounce animation */
.icons li a i:hover {
  animation: bounce 0.5s infinite;
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
.row ul li a:hover i {
  color: #ffffff;
}
</style>