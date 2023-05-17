<template>
    <body>
	<section>
    <h1 class="d-flex justify-content-center mt-2 text-white">Projects</h1>
    <div>
    <div class="container-fluid">
        <div class="row gap-5 mx-3 d-sm-flex justify-content-center">
    <div class="card" v-for="item in projects" :key="item">
			<h5 class="card-title mt-5">{{ item.name }}</h5>
            <img :src="item.image" class="mx-auto d-block" style="width: 15rem;"/>
            <div class="card-body text-black">
                <p class="card-text">{{ item.description }}</p>
                <h5 class="link"><a :href="item.GitHub" target="_blank">Github</a></h5>
                <h5 class="link"><a :href="item.Live" target="_blank">Live</a></h5>
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
                name: "WordPress E-commerce",
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
                Live:"https://buhleqampi-js-calculator.netlify.app"
            },
            {
                name: "Point of Sale",
                image:"https://i.postimg.cc/HxtNbscJ/Point-of-sale.png",
                description:"An end of module project using JavaScript",
                GitHub:"https://github.com/buhleqampi/Javascript-project-2.git",
                Live:"https://js-endof-module-project-2.netlify.app" 
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
.card{
	width: 300px;
	height: 400px;
	margin: 20px;
	box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
	border-radius: 15px;
	justify-content: center;
	align-items: center;
	backdrop-filter: blur(10px);
	position: relative;
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	transition: 0.5s;
	background-color: gray;
	font-family: Georgia, 'Times New Roman', Times, serif
}
.card:hover .link {
	transform: translateY(-20px);
}
/*
img {
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

/* .container .card  {
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

. .card:hover .sci li {
	transform: translateY(0px);
	opacity: 1;
}
*/
.link {
	display:inline;
	color: #fff;
	font-size: 20px;
	padding:5px;
	margin-bottom:5px;
} 
h1{
	font-family: Arial, Helvetica, sans-serif;
}
</style>