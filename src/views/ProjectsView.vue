<template>
    <body>
	<section>
    <h1 class="d-flex justify-content-center mt-2 text-white">Projects</h1>
    <div>
    <div class="container-fluid">
        <div class="row gap-5 mx-1 d-sm-flex justify-content-center">
    <div class="card" v-for="item in projects" :key="item">
			<h5 class="card-title mt-5">{{ item.name }}</h5>
            <img :src="item.image" class="mx-auto d-block" style="width: 15rem;"/>
            <div class="card-body text-black">
                <p class="card-text">{{ item.description }}</p>
              <a :href="item.GitHub" target="_blank" class="github-link"><button type="text" class="btn btn-secondary btn-md github-btn">Github</button></a>
            <a :href="item.Live" target="_blank" class="live-link"><button type="text" class="btn btn-secondary btn-md live-btn">Live</button></a>
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
                description:"I worked in a pair did a full stack project using Node.js",
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
	background:  #1f1f1f;
}
.card{
	width: 300px;
	height: 350px;
	margin: 30px;
	margin-top: 30px;
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
	font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
h1{
	font-family: Arial, Helvetica, sans-serif;
}
.github-link, .live-link  {
	color: #fff;
	display:inline;
	font-size: 20px;
	padding:5px;
	margin-bottom:5px;


}
.github-btn , .live-btn {
	background-color: #025464;
}

</style>