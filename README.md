# Business-portfolio-website-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mr Azhar - Business Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #222;
      color: #fff;
      padding: 20px 40px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    nav {
      background: #444;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: #fff;
      padding: 15px 20px;
      text-decoration: none;
      transition: background 0.3s;
    }
    nav a:hover {
      background: #666;
    }
    section {
      padding: 40px;
      max-width: 1000px;
      margin: auto;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(to right, #0072ff, #00c6ff);
      color: white;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .services, .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0px 3px 8px rgba(0,0,0,0.1);
    }
    .card h3 {
      margin-top: 0;
    }
    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 20px;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .contact-form button {
      background: #0072ff;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }
    .contact-form button:hover {
      background: #005fcc;
    }
  </style>
</head>
<body>

  <header>
    <h1>Mr Azhar</h1>
    <p>Web Developer | Designer | SEO Expert</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Welcome to My Portfolio</h2>
    <p>Showcasing my skills, projects, and services for global clients</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>
      My name is <b>Azhar Mehmood</b>, but you can call me <b>Mr Azhar</b>.  
      I specialize in creating modern websites, user-friendly designs, and SEO strategies 
      that help businesses grow online. With passion and creativity, I aim to deliver 
      top-quality solutions for my clients.  
    </p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="services">
      <div class="card">
        <h3>Web Development</h3>
        <p>Responsive and modern websites built with the latest technology.</p>
      </div>
      <div class="card">
        <h3>Graphic Design</h3>
        <p>Creative and professional designs to enhance brand identity.</p>
      </div>
      <div class="card">
        <h3>SEO Optimization</h3>
        <p>Boost your business visibility and reach more customers online.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2>My Work</h2>
    <div class="portfolio">
      <div class="card">
        <h3>Restaurant Website</h3>
        <p>Developed a modern website for a restaurant business.</p>
      </div>
      <div class="card">
        <h3>Photography Portfolio</h3>
        <p>Created an elegant portfolio site for a professional photographer.</p>
      </div>
      <div class="card">
        <h3>E-commerce Store</h3>
        <p>Designed and built an online store for fashion products.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p style="margin-top:15px;">
      📧 Email: <a href="mailto:mrazhr@gmail.com">mrazhr@gmail.com</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Mr Azhar | All Rights Reserved</p>
  </footer>

</body>
</html>
