<template>
    <body>
	<section>
		<div class="container">
			<div class="card">
				<div class="content">
					<div class="imgBx">
						<img src="https://i.postimg.cc/PxFc5fC1/Portfolio.png" alt="project">
					</div>
					<div class="contentBx">
						<h3>Lion<br><span>Happy Birthday</span></h3>
					</div>
				</div>
				<ul class="sci">
					<li>
						<a href="">happy</a>
					</li>
					<li>
						<a href="">birth</a>
					</li>
					<li>
						<a href="">day</a>
					</li>
				</ul>
			</div>
			<div class="card">
				<div class="content">
					<div class="imgBx">
						<img src="" alt="pic">
					</div>
					<div class="contentBx">
						<h3>Frog<br><span>Happy Birthday</span></h3>
					</div>
				</div>
				<ul class="sci">
					<li>
						<a href="">happy</a>
					</li>
					<li>
						<a href="">birth</a>
					</li>
					<li>
						<a href="">day</a>
					</li>
				</ul>
			</div>
			<div class="card">
				<div class="content">
					<div class="imgBx">
						<img src="" alt="pic">
					</div>
					<div class="contentBx">
						<h3>Giraffe<br><span>Happy Birthday</span></h3>
					</div>
				</div>
				<ul class="sci">
					<li>
						<a href="">happy</a>
					</li>
					<li>
						<a href="">birth</a>
					</li>
					<li>
						<a href="">day</a>
					</li>
				</ul>
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
* {
	margin: 0;
	padding: 0;
}

body {
	display: flex;
	justify-content: center;
	align-items: center;
	flex-wrap: wrap;
	background: #161616;
	min-height: 100vh;
}

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
}

.container .card:hover .content {
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
}

.container .card .sci {
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
}
</style>