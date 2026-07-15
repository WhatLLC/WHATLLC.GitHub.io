
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WHAT LLC | Premier Business Consulting Montana</title>
<!-- Font Awesome Icon CDN Fix -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
<style>
/* BODY background */
body {
  color: var(--text);
  background-color: #f5f7fa;
  /* make sure the path matches where you upload the file in the repo */
  background-image: url('Pictures/flag.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  background-attachment: fixed; /* optional; some mobile browsers ignore this */
  line-height: 1.6;
}

/* Hero section with gradient overlay for contrast */
.hero {
  background-color: #0f1720;
  background-image:
    linear-gradient(rgba(30,61,89,0.6), rgba(17,30,37,0.7)),
    url('Pictures/flag.jpg');
  background-repeat: no-repeat, no-repeat;
  background-position: center top, center top;
  background-size: cover, cover;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
  padding: 0 1rem;
  margin-top: -60px;
}
:root {
--primary: #1e3d59;
--secondary: #17b978;
--dark: #111e25;
--light: #f5f7fa;
--text: #333333;
}
* {
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
body {
color: var(--text);
background-color: #f5f7fa;
background-image: url('../Pictures/flag.jpg');
background-repeat: no-repeat;
background-position: center center;
background-size: cover;
background-attachment: fixed;
line-height: 1.6;
}
/* Navigation */
nav {
background-color: var(--primary);
padding: 1rem 5%;
position: fixed;
width: 100%;
top: 0;
z-index: 1000;
display: flex;
justify-content: space-between;
align-items: center;
box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}
.logo {
color: #fff;
font-size: 1.8rem;
font-weight: 800;
letter-spacing: 1px;
}
.logo span {
color: var(--secondary);
}
.nav-links {
display: flex;
list-style: none;
}
.nav-links li {
margin-left: 2rem;
}
.nav-links a {
color: #fff;
text-decoration: none;
font-weight: 500;
transition: color 0.3s;
}
.nav-links a:hover {
color: var(--secondary);
}
/* Hero Section with Vertical Flag Background */
.hero {
background-color: #0f1720;
background-image: linear-gradient(rgba(30, 61, 89, 0.72), rgba(17, 30, 37, 0.82)), url('../Pictures/flag.jpg');
background-repeat: no-repeat, no-repeat;
background-position: center top, center top;
background-size: cover, cover;
height: 100vh;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
color: #fff;
padding: 0 1rem;
margin-top: -60px;
}
.hero h1 {
font-size: 3.5rem;
margin-bottom: 1rem;
font-weight: 700;
}
.hero p {
font-size: 1.5rem;
max-width: 700px;
margin-bottom: 2rem;
font-weight: 300;
}
.btn {
background-color: var(--secondary);
color: #fff;
padding: 0.8rem 2rem;
border: none;
border-radius: 4px;
font-size: 1.1rem;
font-weight: 600;
cursor: pointer;
text-decoration: none;
transition: background 0.3s, transform 0.2s;
}
.btn:hover {
background-color: #14a066;
transform: translateY(-2px);
}
/* Sections General */
section {
padding: 5rem 10%;
}
.section-title {
text-align: center;
font-size: 2.5rem;
color: var(--primary);
margin-bottom: 3rem;
position: relative;
}
.section-title::after {
content: '';
width: 50px;
height: 4px;
background-color: var(--secondary);
position: absolute;
bottom: -10px;
left: 50%;
transform: translateX(-50%);
}
/* Services Grid */
.services-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
gap: 2rem;
}
.service-card {
background-color: var(--light);
padding: 2.5rem 2rem;
border-radius: 8px;
text-align: center;
transition: transform 0.3s;
}
.service-card:hover {
transform: translateY(-5px);
}
.service-card i {
font-size: 3rem;
color: var(--primary);
margin-bottom: 1.5rem;
}
.service-card h3 {
margin-bottom: 1rem;
color: var(--primary);
}
/* About Section */
.about {
background-color: var(--light);
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
gap: 4rem;
}
.about-content {
flex: 1;
max-width: 900px;
width: 100%;
text-align: center;
}
.about-content p {
margin-bottom: 1.5rem;
font-size: 1.1rem;
}
.about-lead {
display: inline-block;
white-space: nowrap;
}
/* Contact Section */
#contact {
color: #fff;
}
#contact .section-title {
color: #fff;
}
#contact .section-title::after {
background-color: var(--secondary);
}
#contact h3,
#contact p,
#contact .contact-info div {
color: #fff;
}
.contact-container {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
gap: 3rem;
}
.contact-info i {
color: var(--secondary);
margin-right: 1rem;
font-size: 1.2rem;
}
.contact-info div {
margin-bottom: 1.5rem;
display: flex;
align-items: center;
}
form {
display: flex;
flex-direction: column;
}
input, textarea {
padding: 1rem;
margin-bottom: 1rem;
border: 1px solid #ccc;
border-radius: 4px;
font-size: 1rem;
}
textarea {
height: 150px;
resize: vertical;
}
/* Footer */
footer {
background-color: var(--dark);
color: #fff;
text-align: center;
padding: 2rem;
font-size: 0.9rem;
}
/* Responsive Design */
@media (max-width: 768px) {
.nav-links {
display: none;
}
.hero h1 {
font-size: 2.5rem;
}
.hero p {
font-size: 1.1rem;
}
.about {
flex-direction: column;
gap: 2rem;
}
.about-lead {
display: block;
white-space: normal;
}
section {
padding: 4rem 5%;
}
}
</style>
</head>
<body>
<!-- Navigation -->
<nav>
<div class="logo">WHAT<span>LLC</span></div>
<ul class="nav-links">
<li><a href="#home">Home</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#about">About</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<!-- Hero Section -->
<header class="hero" id="home">
<h1>Clarity in Strategy. Precision in Execution of Daily Operations.</h1>
<p>America’s premier consulting firm driving strategic innovation, and operational excellence for businesses and individuals nationwide. We will help you get where you are going knowing WHAT is driving you. </p>
<a href="#contact" class="btn">Know What</a>
</header>

<!-- Services Section -->
<section id="services">
<h2 class="section-title">Our Expertise</h2>
<div class="services-grid">
<div class="service-card">
<i class="fa-solid fa-chart-line"></i>
<h3>Strategic Planning</h3>
<p>We build custom designed and tailored long-term strategic solutions to navigate shifting market demands.</p>
</div>
<div class="service-card">
<i class="fa-solid fa-gears"></i>
<h3>Operational Excellency</h3>
<p>Optimize your mobility, reduce overhead costs, and fine-tune your business infrastructure for peak operational performance.</p>
</div>
<div class="service-card">
<i class="fa-solid fa-arrow-up-right-dots"></i>
<h3>Driven Growth</h3>
<p>Actionable expansion blueprints, financial forecasting, specializing in organic growth and comprehensive market entry analysis for ambitious brands.</p>
</div>
</div>
</section>

<!-- About Section -->
<section id="about" class="about">
<div class="about-content">
<h2 class="section-title">Who We Are</h2>
<p class="about-lead">Based against the rugged backdrop of America, <strong>WHAT LLC</strong> embodies the relentless, grounded, and forward-thinking spirit of Freedom.</p>
<p>We are a premier consulting firm serving clients locally and across the United States.</p>
<p>We cut through the noise to deliver blunt, high-utility solutions.</p>
<p>Our mission is built on answering the question of WHAT.</p>
<p><em>WHAT is your next move.</em></p>
</div>
</section>

<!-- Contact Section -->
<section id="contact">
<h2 class="section-title">Get Informed about WHAT</h2>
<div class="contact-container">
<div class="contact-info">
<h3>Let's Solve What</h3>
<p style="margin-bottom: 0.75rem; margin-top: 1rem;">Ready to drive your business?</p>
<p style="margin-bottom: 2rem;">Reach out today to schedule a consult.</p>
<div><i class="fa-solid fa-location-dot"></i> Saint Ignatius, Montana, USA</div>
<div><i class="fa-solid fa-envelope"></i> LLCME@icloud.com</div>
<div><i class="fa-solid fa-phone"></i> +1 (772) 263-2090</div>
</div>
<form onsubmit="event.preventDefault(); alert('WHAT up. Thank you for reaching out to WHAT LLC! Our team will tell you WHAT shortly.');">
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email Address" required>
<input type="text" placeholder="Subject / Business Type" required>
          <button type="submit" class="btn">Send Message</button>
        </form>

    </div>
  </section>
</body>
</html>
