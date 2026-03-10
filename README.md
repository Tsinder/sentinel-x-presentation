# sentinel-x-presentation
sentinel-x-presentation │ ├── index.html ├── style.css ├── script.js └── README.md
<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sentinel-X | Planetary Intelligence</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<div class="presentation">

<section class="slide">
<h1>Sentinel-X</h1>
<h2>Planetary Intelligence Infrastructure</h2>

<p>Architect & Inventor</p>
<h3>Vadym Tsinderhoz</h3>

<p>Telegram: @Tsinder</p>
</section>


<section class="slide">
<h2>Mission Overview</h2>

<ul>
<li>Planetary monitoring architecture</li>
<li>AI powered threat analysis</li>
<li>Satellite & sensor network</li>
<li>Digital Twin Earth simulation</li>
</ul>

</section>


<section class="slide">
<h2>Global Security Landscape</h2>

<ul>
<li>Hypersonic systems</li>
<li>Autonomous warfare</li>
<li>Space domain militarization</li>
<li>AI accelerated conflicts</li>
</ul>

</section>


<section class="slide">

<h1>Sentinel-X Vision</h1>

<h3>Planetary Intelligence Infrastructure</h3>

<p>Architect & Inventor  
Vadym Tsinderhoz</p>

<p>Telegram: @Tsinder</p>

</section>

</div>

<script src="script.js"></script>

</body>

</html>body {

margin:0;

font-family:Arial;

background:#05070d;

color:white;

overflow:hidden;

}

.presentation {

display:flex;

transition: transform 0.7s ease;

}

.slide {

min-width:100vw;

height:100vh;

display:flex;

flex-direction:column;

justify-content:center;

align-items:center;

text-align:center;

padding:40px;

}

h1 {

font-size:70px;

}

h2 {

font-size:40px;

margin-bottom:30px;

}

ul {

font-size:24px;

list-style:none;

padding:0;

}

li {

margin:12px;

}const slides = document.querySelectorAll(".slide")

const container = document.querySelector(".presentation")

let index = 0

function updateSlide(){

container.style.transform = `translateX(-${index * 100}vw)`

}

document.addEventListener("keydown", e => {

if(e.key === "ArrowRight"){

index++

}

if(e.key === "ArrowLeft"){

index--

}

if(index < 0) index = 0

if(index > slides.length - 1)

index = slides.length - 1

updateSlide()

})
