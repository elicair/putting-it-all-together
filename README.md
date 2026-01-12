# putting-it-all-together
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Home - My Website</title>
<link rel="stylesheet" href="styles.css" />
<meta name="description" content="Welcome to my accessible and SEO-friendly website." />
</head>
<body>
<header>
<h1>Welcome to My Accessible Website</h1>
<nav aria-label="Main Navigation" class="nav-container">
<ul class="nav-list">
<li><a href="index.html" aria-current="page">Home</a></li>
<li><a href="about.html">About</a></li>
<li><a href="services.html">Services</a></li>
<li><a href="gallery.html">Gallery</a></li>
<li><a href="contact.html">Contact</a></li>
<li><a href="blog.html">Blog</a></li>
</ul>
</nav>
</header>

<main>
<section class="intro">
<h2>Discover Our Mission</h2>
<p>We aim to provide accessible, engaging, and informative content for all visitors.</p>
</section>

<!-- Flexbox layout for features -->
<section class="features flex-container">
<div class="feature-box">
<img src="images/feature1.jpg" alt="Feature 1 illustration" />
<figcaption>Feature 1: Accessibility</figcaption>
<p>Ensuring everyone can access our content.</p>
</div>
<div class="feature-box">
<img src="images/feature2.jpg" alt="Feature 2 illustration" />
<figcaption>Feature 2: Performance</figcaption>
<p>Optimized for fast loading speeds.</p>
</div>
</section>

<!-- Lists -->
<section class="lists">
<h3>Our Services</h3>
<ul class="simple-list">
<li>Web Design</li>
<li>Development</li>
<li>SEO Optimization</li>
</ul>

<h3>Project Phases</h3>
<ul class="complex-list">
<li>Planning
<ul>
<li>Research</li>
<li>Wireframing</li>
</ul>
</li>
<li>Design
<ul>
<li>Prototype creation</li>
<li>Client feedback</li>
</ul>
</li>
<li>Development
<ul>
<li>Front-end coding</li>
<li>Back-end setup</li>
</ul>
</li>
</ul>
</section>

<!-- Complex Table -->
<section class="pricing-table">
<h3>Pricing Plans</h3>
<table class="styled-table">
<thead>
<tr>
<th>Plan</th>
<th>Features</th>
<th>Price</th>
</tr>
</thead>
<tbody>
<tr>
<td>Basic</td>
<td>Basic features</td>
<td>$99/month</td>
</tr>
<tr>
<td>Pro</td>
<td>All features + support</td>
<td>$199/month</td>
</tr>
<tr>
<td>Enterprise</td>
<td>Custom solutions</td>
<td>Contact us</td>
</tr>
</tbody>
</table>
</section>

<!-- Contact Form -->
<section class="contact-form">
<h3>Contact Us</h3>
<form action="submit_form.php" method="POST" aria-labelledby="contact-form-label">
<label id="contact-form-label" for="name">Name:</label>
<input type="text" id="name" name="name" required />

<label for="email">Email:</label>
<input type="email" id="email" name="email" required />

<label for="message">Message:</label>
<textarea id="message" name="message" rows="4" required></textarea>

<button type="submit">Send</button>
</form>
</section>

<!-- Video -->
<section class="video-section">
<h3>Introduction Video</h3>
<video controls aria-label="Introduction video describing our services" width="600" poster="images/video-poster.jpg">
<source src="videos/intro.mp4" type="video/mp4" />
Your browser does not support the video tag.
</video>
</section>
</main>

<footer>
<p>&copy; 2024 My Accessible Website</p>
<p>
For more info, visit our <a href="https://externalresource.com" target="_blank" rel="noopener noreferrer">external resource</a>.
</p>
</footer>
</body>
</html>
    
