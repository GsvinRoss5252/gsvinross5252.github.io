# gsvinross5252.github.io

<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8" /> <meta name="viewport" content="width=device-width, initial-scale=1.0"/> <title>L&A Lawn Care Services</title> <link rel="stylesheet" href="styles.css"/> </head> <body> <header> <h1>L&A Lawn Care Services</h1> <nav> <ul> <li><a href="index.html">Home</a></li> <li><a href="services.html">Services</a></li> <li><a href="about.html">About</a></li> <li><a href="contact.html">Contact</a></li> </ul> </nav> </header>

<section class="hero"> <h2>Beautiful Lawns. Reliable Service.</h2> <p>Your lawn deserves the best — and we deliver.</p> </section>

<section class="intro"> <h3>Welcome to L&A Lawn Care</h3> <p>We specialize in making your yard look its best, all year long. With years of experience and a commitment to quality, you can count on us.</p> </section>

<footer> <p>© 2025 L&A Lawn Care Services</p> </footer> </body> </html>

<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8" /> <meta name="viewport" content="width=device-width, initial-scale=1.0"/> <title>Services - L&A Lawn Care</title> <link rel="stylesheet" href="styles.css"/> </head> <body> <header> <h1>L&A Lawn Care Services</h1> <nav> <ul> <li><a href="index.html">Home</a></li> <li><a href="services.html">Services</a></li> <li><a href="about.html">About</a></li> <li><a href="contact.html">Contact</a></li> </ul> </nav> </header>

<section class="content"> <h2>Our Services</h2> <ul class="services-list"> <li>Lawn Mowing & Maintenance</li> <li>Weed Control</li> <li>Fertilization & Soil Treatment</li> <li>Mulching & Edging</li> <li>Seasonal Cleanups</li> </ul> </section>

<footer> <p>© 2025 L&A Lawn Care Services</p> </footer> </body> </html>

<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8" /> <meta name="viewport" content="width=device-width, initial-scale=1.0"/> <title>About Us - L&A Lawn Care</title> <link rel="stylesheet" href="styles.css"/> </head> <body> <header> <h1>L&A Lawn Care Services</h1> <nav> <ul> <li><a href="index.html">Home</a></li> <li><a href="services.html">Services</a></li> <li><a href="about.html">About</a></li> <li><a href="contact.html">Contact</a></li> </ul> </nav> </header>

<section class="content"> <h2>About Us</h2> <p>L&A Lawn Care is a locally owned business dedicated to keeping your lawn healthy and beautiful. Our team is experienced, dependable, and committed to top-notch service.</p> </section>

<footer> <p>© 2025 L&A Lawn Care Services</p> </footer> </body> </html>

<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8" /> <meta name="viewport" content="width=device-width, initial-scale=1.0"/> <title>Contact - L&A Lawn Care</title> <link rel="stylesheet" href="styles.css"/> </head> <body> <header> <h1>L&A Lawn Care Services</h1> <nav> <ul> <li><a href="index.html">Home</a></li> <li><a href="services.html">Services</a></li> <li><a href="about.html">About</a></li> <li><a href="contact.html">Contact</a></li> </ul> </nav> </header>

<section class="content"> <h2>Contact Us</h2> <form id="contact-form"> <label for="name">Name:</label> <input type="text" id="name" name="name" required/>

<label for="email">Email:</label>
<input type="email" id="email" name="email" required/>

<label for="message">Message:</label>
<textarea id="message" name="message" required></textarea>

<button type="submit">Send Message</button>
</form>
<p id="form-status"></p>


</section>

<footer> <p>© 2025 L&A Lawn Care Services</p> </footer>

<script> const form = document.getElementById('contact-form'); const status = document.getElementById('form-status'); form.addEventListener('submit', function(e) { e.preventDefault(); status.textContent = "Thanks for reaching out! We'll get back to you soon."; form.reset(); }); </script> </body> </html>

body { font-family: Arial, sans-serif; margin: 0; background: #f7fdf7; color: #333; }

header { background: #2e7d32; color: white; padding: 1rem; text-align: center; }

nav ul { list-style: none; padding: 0; display: flex; justify-content: center; margin-top: 1rem; }

nav li { margin: 0 1rem; }

nav a { color: Green; text-decoration: none; font-weight: bold; }

.hero { background: url('https://images.unsplash.com/photo-1600607687993-019d3e3d655c?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover; color: Green; text-align: center; padding: 4rem 1rem; }

.content, .intro { padding: 2rem; text-align: center; }

.services-list { list-style: square; max-width: 600px; margin: auto; text-align: left; }

form { max-width: 500px; margin: auto; display: flex; flex-direction: column; gap: 1rem; }

input, textarea { padding: 0.5rem; border: 1px solid #ccc; border-radius: 4px; }

button { background: #008000; color: green; border: none; padding: 0.7rem; border-radius: 4px; cursor: pointer; }

button:hover { background: #1b5e20; }

footer { background: #e0e0e0; text-align: center; padding: 1rem; margin-top: 2rem; }
