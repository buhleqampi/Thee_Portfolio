<template>
    <body>
	<section>
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
	</section>
</body>
</template>
<script>
export default {
    data () {
        return {
            projects: [
			{
                name: "WordPress E-commerce website",
                image:"https://i.postimg.cc/3JdfYTjr/Screenshot-2023-05-16-115704.png",
                description:"Got  to work in a team of 4 collegues and create an e-commerce website using WordPress.",
                GitHub:"",
                Live:"https://dev-alphapeakexplore.pantheonsite.io/" 
            },
			{
                name: "Capstone Project",
                image:"https://i.postimg.cc/z3mMb25P/Screenshot-2023-05-16-113928.png",
                description:"A capstone project that tests my full stack development of skills I have learnt",
                GitHub:"https://github.com/buhleqampi/second_handy.git",
                Live:"https://capstoneproject-7d162.web.app/" 
            },
			{	name: "Node Full Stack Project",
                image:"https://i.postimg.cc/cL4nVQVV/Screenshot-2023-05-16-114358.png",
                description:"I worked in a pair did a full stack project using Node",
                GitHub:"https://github.com/zoefaithdaniels/Node-FullstackProject.git",
                Live:"http://vue-eomp.firebaseapp.com/"
            },
			{
                name: "JS Calculator",
                image:"https://i.postimg.cc/Hspt1pkK/Screenshot-2023-05-16-114142.png",
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
                name: "HTML/CSS Portfolio",
                image:"https://i.postimg.cc/PxFc5fC1/Portfolio.png",
                description:"This was my first project in the form of a personal portfolio. I used HTML and CSS.",
                GitHub:"https://github.com/buhleqampi/Portfolio.git",
                Live:"https://buhle-qampi-portfolio.netlify.app"
            }
            ]
        }
    }
    
}
</script>
<style scoped>
body {
	display: flex;
	justify-content: center;
	align-items: center;
	flex-wrap: wrap;
	background:  #1f1f1f;;
	min-height: 100vh;
}
/* 
section::before {
	content: '';
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: linear-gradient(#DA22FF, #9733EE);
	clip-path: circle(30% at right 70%);
}
.container {
	position: relative;
	z-index: 1;
	display: flex;
	justify-content: center;
	align-items: center;
	flex-wrap: wrap;
	margin: 40px 0;
}

.container .card {
	position: relative;
	width: 300px;
	height: 400px;
	background: rgba(255, 255, 255, 0.05);
	margin: 20px;
	box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
	border-radius: 15px;
	display: flex;
	justify-content: center;
	align-items: center;
	backdrop-filter: blur(10px);
}

.container .card .content {
	position: relative;
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	transition: 0.5s;
} */
.card {
    background-color: gray;
    background: rgba(82, 78, 78, 0.5);
    border-radius: 16px;
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(9.9px);
    -webkit-backdrop-filter: blur(9.9px);
    border: 1px solid rgba(82, 78, 78, 0.26);
}
/* .container .card:hover .content {
	transform: translateY(-20px);
}

.container .card .content .imgBx {
	position: relative;
	width: 150px;
	height: 150px;
	overflow: hidden;
}

.container .card .content .imgBx img {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	object-fit: center;
}

.container .card .content .contentBx h3 {
	color: #fff;
	text-transform: uppercase;
	letter-spacing: 2px;
	font-weight: 500;
	font-size: 18px;
	text-align: center;
	margin: 20px 0 10px;
	line-height: 1.1em;
}

.container .card .content .contentBx h3 span {
	font-size: 12px;
	font-weight: 300;
	text-transform: initial;
} */

/* .container .card .sci {
	position: absolute;
	bottom: 50px;
	display: flex;
}

.container .card .sci li {
	list-style: none;
	margin: 0 10px;
	transform: translateY(40px);
	transition: 0.5s;
	opacity: 0;
}

.container .card:hover .sci li {
	transform: translateY(0px);
	opacity: 1;
}

.container .card .sci li a {
	color: #fff;
	font-size: 20px;
} */
</style>