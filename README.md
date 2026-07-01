# oyindamola.github.io
<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Oyindamola | Official Website</title>

<link rel="stylesheet" href="style.css">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

</head>

<body>

<header>

<nav>

<h2>OYINDAMOLA</h2>

<ul>

<li><a href="#about">About</a></li>

<li><a href="#gallery">Gallery</a></li>

<li><a href="#contact">Contact</a></li>

</ul>

</nav>

</header>

<section class="hero">

<div class="hero-text">

<h1>Hello, I'm <span>Oyindamola</span></h1>

<p>
Content Creator • Influencer • Brand Ambassador
</p>

<a href="https://www.tiktok.com/@itzoyindamola6" target="_blank" class="btn">Follow on TikTok</a>

<a href="https://wa.me/2349035401066" class="btn2">Book Me</a>

</div>

<div class="hero-image">

<img src="assets/IMG_0844.jpg">

</div>

</section>

<section id="about">

<h2>About Me</h2>

<p>

I'm Oyindamola, a passionate content creator who enjoys creating engaging videos, fashion content, lifestyle inspiration, and collaborating with brands.

I love connecting with audiences through creativity and authenticity.

</p>

</section>

<section id="gallery">

<h2>Gallery</h2>

<div class="gallery">

<img src="assets/IMG_0834.jpg">

</div>

</section>

<section id="contact">

<h2>Let's Work Together</h2>

<p>

Phone: 09035401066

</p>

<p>

TikTok:
<a href="https://www.tiktok.com/@itzoyindamola6">

@itzoyindamola6

</a>

</p>

<a href="https://wa.me/2349035401066" class="btn">

WhatsApp

</a>

</section>

<footer>

<p>

© 2026 Oyindamola

</p>

</footer>

<script src="script.js"></script>

</body>

</html>
*{

margin:0;
padding:0;
box-sizing:border-box;

font-family:Poppins,sans-serif;

}

body{

background:#111;

color:white;

}

header{

padding:20px 10%;

background:#000;

position:fixed;

width:100%;

}

nav{

display:flex;

justify-content:space-between;

align-items:center;

}

nav ul{

display:flex;

list-style:none;

}

nav li{

margin-left:30px;

}

nav a{

color:white;

text-decoration:none;

}

.hero{

display:flex;

justify-content:space-between;

align-items:center;

padding:150px 10%;

flex-wrap:wrap;

}

.hero img{

width:350px;

border-radius:20px;

box-shadow:0 0 30px deeppink;

}

.hero-text{

max-width:500px;

}

.hero h1{

font-size:55px;

}

.hero span{

color:#ff2d75;

}

.btn,.btn2{

display:inline-block;

padding:14px 30px;

margin-top:20px;

margin-right:10px;

background:#ff2d75;

color:white;

text-decoration:none;

border-radius:40px;

transition:.4s;

}

.btn:hover,.btn2:hover{

background:white;

color:#111;

}

section{

padding:90px 10%;

}

.gallery{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(300px,1fr));

gap:20px;

}

.gallery img{

width:100%;

border-radius:20px;

}

footer{

text-align:center;

padding:30px;

background:#000;

}

@media(max-width:768px){

.hero{

flex-direction:column;

text-align:center;

}

.hero img{

margin-top:40px;

width:280px;

}

}
window.addEventListener("scroll",function(){

const header=document.querySelector("header");

header.classList.toggle("sticky",window.scrollY>0);

});
# Oyindamola Official Website

Modern Portfolio Website

Features
- Responsive
- Mobile Friendly
- Dark Theme
- Gallery
- TikTok Button
- WhatsApp Button
- GitHub Pages Ready
