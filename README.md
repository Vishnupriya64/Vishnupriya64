
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Business Services</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background: #0a0a23;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #161641;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
      background: #eaeaea;
    }
    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .service-card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .service-card:hover {
      transform: translateY(-5px);
    }
    .service-card h3 {
      margin-top: 0;
      color: #1a1a80;
    }
    footer {
      background: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>My Business</h1>
  <p>Your trusted partner for professional services</p>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">Services</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>

<section class="hero">
  <h1>Our Services</h1>
  <p>We offer high-quality, reliable services tailored to your needs.</p>
</section>

<section class="services">
  <div class="service-card">
    <h3>Content Writing</h3>
    <p>Get engaging and original content written by our expert writers.</p>
  </div>
  <div class="service-card">
    <h3>PowerPoint Design</h3>
    <p>Professional slide decks for business, education, or marketing.</p>
  </div>
  <div class="service-card">
    <h3>Poster Creation</h3>
    <p>Eye-catching posters for academic, commercial, or event needs.</p>
  </div>
  <div class="service-card">
    <h3>Academic Assistance</h3>
    <p>Help with assignments, research reports, and formatting.</p>
  </div>
</section>

<footer>
  <p>© 2025 My Business | All rights reserved.</p>
</footer>

</body>
</html>
