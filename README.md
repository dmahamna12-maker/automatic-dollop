<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">

<title>City Care Hospital</title>

<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:#f2f7fb;
color:#333;
}

header{

background:linear-gradient(135deg,#0077ff,#00bcd4);
color:#fff;
padding:25px;
text-align:center;

}

header h1{
font-size:32px;
}

header p{
margin-top:10px;
font-size:18px;
}

nav{

display:flex;
justify-content:center;
flex-wrap:wrap;
background:#0056b3;

}

nav a{

color:white;
text-decoration:none;
padding:15px 18px;
font-weight:bold;

}

nav a:hover{

background:#003d80;

}
.logo{
width:100px;
height:100px;
border-radius:50%;
background:white;
padding:5px;
margin-bottom:15px;
object-fit:cover;
}
.hero{

padding:70px 20px;
text-align:center;
background:white;

}

.hero h2{

font-size:36px;
color:#0077ff;
margin-bottom:15px;

}

.hero p{

font-size:18px;
margin-bottom:25px;

}

.btn{

display:inline-block;
padding:14px 28px;
margin:8px;
border-radius:8px;
text-decoration:none;
font-weight:bold;
color:white;
transition:.3s;

}

.call{

background:#28a745;

}

.call:hover{

background:#1e7e34;

}

.whatsapp{

background:#25D366;

}

.whatsapp:hover{

background:#18b756;

}

.direction{

background:#ff9800;

}

.direction:hover{

background:#e68900;

}

.share{

background:#0077ff;

}

.share:hover{

background:#0056b3;

}

section{

padding:60px 20px;

}

.title{

text-align:center;
font-size:30px;
margin-bottom:35px;
color:#0077ff;

}

.cards{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;

}

.card{

background:white;
padding:25px;
border-radius:12px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
text-align:center;
transition:.3s;

}

.card:hover{

transform:translateY(-5px);

}

.card i{

font-size:45px;
color:#0077ff;
margin-bottom:15px;

}

.card h3{

margin-bottom:10px;

}

.review-box{

max-width:700px;
margin:auto;
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.1);

}

.review-box input,
.review-box textarea{

width:100%;
padding:12px;
margin:10px 0;
border:1px solid #ccc;
border-radius:8px;

}

.review-box button{

width:100%;
padding:14px;
background:#0077ff;
color:white;
border:none;
border-radius:8px;
font-size:18px;
cursor:pointer;

}

.review-box button:hover{

background:#0056b3;

}

.stars{

font-size:35px;
text-align:center;
margin:20px 0;

}

.stars i{

cursor:pointer;
color:#ccc;
transition:.3s;

}

.stars i.active{

color:gold;

}

footer{

background:#003d80;
color:white;
padding:20px;
text-align:center;

}

.float{

position:fixed;
right:20px;
bottom:20px;
display:flex;
flex-direction:column;
gap:12px;
z-index:999;

}

.float a{

width:55px;
height:55px;
border-radius:50%;
display:flex;
justify-content:center;
align-items:center;
color:white;
font-size:24px;
text-decoration:none;

}

.float .w{

background:#25D366;

}

.float .c{

background:#28a745;

}

@media(max-width:700px){

.hero h2{

font-size:28px;

}

nav{

flex-direction:column;

}

}

</style>

</head>

<body>
<header>

<img src="https://images.jdmagicbox.com/v2/comp/delhi/f6/011pxx11.xx11.230405164310.g6f6/catalogue/sgs-multispeciality-hospital-nangloi-delhi-dermatologists-1o5jhndclk-250.jpg"
alt="Hospital Logo"
class="logo">

<h1>SGS Multispeciality Hospital</h1>

<p>24×7 Emergency • Best Doctors • Quality Healthcare</p>

</header>
<nav>

<a href="#about">About</a>

<a href="#services">Services</a>

<a href="#doctor">Doctors</a>

<a href="#review">Reviews</a>

<a href="#contact">Contact</a>

</nav>

<section class="hero">

<h2>Your Health Is Our Priority</h2>

<p>Book Appointment • Call • WhatsApp • Directions</p>

<a href="tel:+919876543210" class="btn call">
<i class="fa-solid fa-phone"></i>
Call Now
</a>

<a href="https://wa.me/919876543210" class="btn whatsapp" target="_blank">
<i class="fab fa-whatsapp"></i>
WhatsApp
</a>

<a href="https://maps.google.com" class="btn direction" target="_blank">
<i class="fa-solid fa-location-dot"></i>
Direction
</a>

<a href="#" class="btn share" onclick="shareSite()">
<i class="fa-solid fa-share"></i>
Share
</a>

</section>

<section id="about">

<h2 class="title">About Hospital</h2>

<div class="cards">

<div class="card">

<i class="fa-solid fa-hospital"></i>

<h3>24×7 Emergency</h3>

<p>Emergency doctors and ambulance available day & night.</p>

</div>

<div class="card">

<i class="fa-solid fa-user-doctor"></i>

<h3>Experienced Doctors</h3>

<p>Qualified specialists with years of experience.</p>

</div>

<div class="card">

<i class="fa-solid fa-heart-pulse"></i>

<h3>Modern Equipment</h3>

<p>Digital X-Ray, ICU, Lab, Pharmacy and more.</p>

</div>

</div>

</section>
<!-- SERVICES -->

<section id="services">

<h2 class="title">Our Services</h2>

<div class="cards">

<div class="card">
<i class="fa-solid fa-stethoscope"></i>
<h3>General OPD</h3>
<p>Daily OPD consultation with expert doctors.</p>
</div>

<div class="card">
<i class="fa-solid fa-truck-medical"></i>
<h3>24×7 Ambulance</h3>
<p>Emergency ambulance available anytime.</p>
</div>

<div class="card">
<i class="fa-solid fa-bed-pulse"></i>
<h3>ICU Care</h3>
<p>Advanced ICU with modern equipment.</p>
</div>

<div class="card">
<i class="fa-solid fa-x-ray"></i>
<h3>X-Ray & Lab</h3>
<p>Digital X-Ray, Blood Test and Diagnostics.</p>
</div>

<div class="card">
<i class="fa-solid fa-pills"></i>
<h3>Pharmacy</h3>
<p>24 Hours Medicine Store.</p>
</div>

<div class="card">
<i class="fa-solid fa-heart"></i>
<h3>Heart Care</h3>
<p>Experienced cardiology specialists.</p>
</div>

</div>

</section>

<!-- DOCTORS -->

<section id="doctor">

<h2 class="title">Our Doctors</h2>

<div class="cards">

<div class="card">
<img src="https://via.placeholder.com/120" style="border-radius:50%;">
<h3>Dr. Amit Sharma</h3>
<p>Cardiologist</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/120" style="border-radius:50%;">
<h3>Dr. Neha Verma</h3>
<p>Orthopedic Specialist</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/120" style="border-radius:50%;">
<h3>Dr. Raj Singh</h3>
<p>General Physician</p>
</div>

</div>

</section>

<!-- REVIEW -->

<section id="review">

<h2 class="title">Patient Reviews</h2>

<div class="review-box">

<h3 style="text-align:center;">Rate Our Hospital</h3>

<div class="stars">

<i class="fa-solid fa-star" data-value="1"></i>
<i class="fa-solid fa-star" data-value="2"></i>
<i class="fa-solid fa-star" data-value="3"></i>
<i class="fa-solid fa-star" data-value="4"></i>
<i class="fa-solid fa-star" data-value="5"></i>

</div>

<input type="text" id="name" placeholder="Patient Name">

<textarea id="reviewText"
placeholder="Write your review..."
rows="5"></textarea>

<button onclick="submitReview()">
Submit Review
</button>

<div id="reviews"
style="margin-top:25px;"></div>

</div>

</section>

<!-- CONTACT -->

<section id="contact">

<h2 class="title">Contact Us</h2>

<div class="cards">

<div class="card">

<i class="fa-solid fa-phone"></i>

<h3>Call</h3>

<p>+91 9876543210</p>

<a href="tel:+919876543210" class="btn call">
Call Now
</a>

</div>

<div class="card">

<i class="fab fa-whatsapp"></i>

<h3>WhatsApp</h3>

<p>Chat with Hospital</p>

<a href="https://wa.me/919876543210"
target="_blank"
class="btn whatsapp">
Open WhatsApp
</a>

</div>

<div class="card">

<i class="fa-solid fa-location-dot"></i>

<h3>Hospital Location</h3>

<p>Google Maps Direction</p>

<a href="https://maps.google.com"
target="_blank"
class="btn direction">
Get Direction
</a>

</div>

</div>

</section>

<!-- Floating Buttons -->

<div class="float">

<a href="https://wa.me/919876543210"
target="_blank"
class="w">

<i class="fab fa-whatsapp"></i>

</a>

<a href="tel:+919876543210"
class="c">

<i class="fa-solid fa-phone"></i>

</a>

</div>
<script>

// ===== Share Website =====
function shareSite(){

const shareData = {
title: "City Care Hospital",
text: "Visit City Care Hospital",
url: window.location.href
};

if(navigator.share){

navigator.share(shareData);

}else{

navigator.clipboard.writeText(window.location.href);

alert("Website link copied successfully.");

}

}

// ===== Star Rating =====

let rating = 0;

const stars = document.querySelectorAll(".stars i");

stars.forEach((star,index)=>{

star.addEventListener("click",()=>{

rating=index+1;

stars.forEach((s,i)=>{

if(i<rating){

s.classList.add("active");

}else{

s.classList.remove("active");

}

});

});

});

// ===== Submit Review =====

function submitReview(){

let name=document.getElementById("name").value.trim();

let review=document.getElementById("reviewText").value.trim();

if(name==="" || review===""){

alert("Please enter your name and review.");

return;

}

if(rating===0){

alert("Please select star rating.");

return;

}

let starsText="";

for(let i=0;i<rating;i++){

starsText+="⭐";

}

let box=document.getElementById("reviews");

box.innerHTML += `

<div style="
background:#f7f7f7;
padding:15px;
border-radius:10px;
margin-top:15px;
box-shadow:0 2px 8px rgba(0,0,0,.1);
">

<h3>${name}</h3>

<p style="color:orange;font-size:18px;">
${starsText}
</p>

<p>${review}</p>

</div>

`;

document.getElementById("name").value="";

document.getElementById("reviewText").value="";

rating=0;

stars.forEach(star=>star.classList.remove("active"));

alert("Thank you for your review!");

}

// ===== Optional Appointment Button =====

function bookAppointment(){

alert("Appointment request received. We will contact you soon.");

}

// ===== Welcome =====

window.onload=function(){

console.log("City Care Hospital Website Loaded");

};

</script>

</body>
</html>
