<template>
    <div class="container px-5">
    <div class="row" style="height: 100%;">
        
        <h1 class="d-flex justify-content-center mt-2 text-white">PROJECTS</h1>
    <div>
    <div class="container-fluid">
        <div class="row gap-5 mx-3 d-sm-flex justify-content-center">
    <div class="card" v-for="item in projects" :key="item">
            <img :src="item.image" class="mx-auto d-block" style="width: 15rem;"/>
            <div class="card-body">
                <h5 class="card-title">{{ item.name }}</h5>
                <p class="card-text">{{ item.description }}</p>
                <h5><a :href="item.GitHub" target="_blank">Github</a></h5>
                <h5><a :href="item.Netlify" target="_blank">Netlify</a></h5>
            </div>
        </div>
    </div>
    </div>
    </div>
    </div>
    </div>
</template>
<script>
export default {
    data () {
        return {
            projects: [
                {
                name: "HTML/CSS Portfolio",
                image:"https://i.postimg.cc/PxFc5fC1/Portfolio.png",
                description:"This was my first project in the form of a personal portfolio. I used HTML and CSS.",
                GitHub:"https://github.com/buhleqampi/Portfolio.git",
                Netlify:"https://buhle-qampi-portfolio.netlify.app"
                },
                {name: "E-commerce Website",
                image:"https://i.postimg.cc/NFn5DX5L/E-Commerce.png",
                description:"E-commerce I used HTML and CSS.",
                GitHub:"https://github.com/buhleqampi/Ecommerce.git",
                Netlify:"https://buhleqampi-ecommerce-site.netlify.app/"
                },
                {
                name: "JS Calculator",
                image:"https://i.postimg.cc/3NtwRvgn/Calculator.png",
                description:"E-commerce I used HTML/CSS and JavaScript.",
                GitHub:"https://github.com/buhleqampi/Javascript-calculator.git",
                Netlify:"https://buhleqampi-js-calculator.netlify.app"
                },
                {
                name: "Point of Sale",
                image:"https://i.postimg.cc/HxtNbscJ/Point-of-sale.png",
                description:"An end of module project using JavaScript",
                GitHub:"https://github.com/buhleqampi/Javascript-project-2.git",
                Netlify:"https://js-endof-module-project-2.netlify.app" 
                },
                {
                name: "Vue Basics Exercise",
                image:"https://i.postimg.cc/85K5kvdw/Vue.png",
                description:"Got to work around with Vue basics and apply the framework to build an app.",
                GitHub:"https://github.com/buhleqampi/Vue.js-first-project.git",
                Netlify:"https://capable-crumble-edce9e.netlify.app" 
                },
                {
                name: "My first coding project",
                image:"https://i.postimg.cc/76ht5ghm/First-portfolio.png",
                description:"Created a portfolio for my first coding project using HTML/CSS",
                GitHub:"https://github.com/buhleqampi/My-Portfolio.git",
                Netlify:"https://buhleqampi-1stportfolio.netlify.app/" 
                },

            ]
        }
    }
    
}
</script>
<style scoped>
.card {
    background-color: white;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    width: 20rem;
}
.card:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);  
}
.card-body {
    padding: 2px 16px;
}
button {
    padding:2px;
}
.container {
    background-image:url(https://i.postimg.cc/wxQhXrTv/alt-background.jpg);
}
</style>