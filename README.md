<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nigeria Tech Academy</title>
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
      body {
        font-family: 'Roboto', sans-serif;
        line-height: 1.6;
        margin: 0;
        padding: 0;
        background: #f9fafc;
        color: #333;
      }

      header {
        background: rgba(0, 40, 80, 0.9);
        color: white;
        padding: 12px 20px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        position: sticky;
        top: 0;
        z-index: 1000;
        backdrop-filter: blur(4px);
      }

      header .logo {
        font-size: 1.5em;
        font-weight: 700;
        letter-spacing: 1px;
      }

      nav a {
        color: white;
        text-decoration: none;
        margin-left: 15px;
        font-weight: 500;
      }

      nav a:hover {
        text-decoration: underline;
      }

      .hero {
        background: linear-gradient(rgba(0,40,80,0.7), rgba(0,40,80,0.7)),
          url("https://images.unsplash.com/photo-1522202176988-66273c2fd55f?fit=crop&w=1350&q=80") no-repeat center center/cover;
        color: white;
        text-align: center;
        padding: 100px 20px;
      }

      .hero h1 {
        font-size: 2.8em;
        margin-bottom: 10px;
      }

      .hero p {
        font-size: 1.2em;
        margin-bottom: 20px;
      }

      .hero a {
        background: #00bcd4;
        color: white;
        padding: 12px 24px;
        border-radius: 25px;
        text-decoration: none;
        font-weight: bold;
        transition: background 0.3s;
      }

      .hero a:hover {
        background: #0097a7;
      }

      main {
        padding: 40px 20px;
        max-width: 1100px;
        margin: auto;
      }

      h2 {
        text-align: center;
        margin-bottom: 30px;
        font-size: 2em;
        color: #002850;
      }

      .cards {
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        justify-content: center;
      }

      .card {
        background: white;
        padding: 20px;
        border-radius: 8px;
        flex: 1;
        min-width: 250px;
        max-width: 300px;
        box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        transition: transform 0.3s;
      }

      .card:hover {
        transform: translateY(-5px);
      }

      .card a {
        display: inline-block;
        margin-top: 10px;
        color: #00bcd4;
        text-decoration: none;
        font-weight: bold;
      }

      .card a:hover {
        text-decoration: underline;
      }

      #testimonials, #newsletter, #contact {
        margin: 40px 20px;
        text-align: center;
      }

      #testimonials {
        background: #e3f2fd;
        padding: 30px;
        border-radius: 8px;
      }

      #testimonials blockquote {
        font-style: italic;
        margin: 10px auto;
      }

      #newsletter input {
        padding: 10px;
        width: 250px;
        max-width: 80%;
        border: 1px solid #ccc;
        border-radius: 4px;
      }

      #newsletter button {
        padding: 10px 15px;
        background: #00bcd4;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        margin-left: 5px;
      }

      #newsletter button:hover {
        background: #0097a7;
      }

      #contact form {
        max-width: 500px;
        margin: auto;
        text-align: left;
      }

      #contact input, #contact textarea {
        width: 100%;
        padding: 10px;
        margin-top: 6px;
        border: 1px solid #ccc;
        border-radius: 4px;
      }

      #contact button {
        background: #00bcd4;
        color: white;
        padding: 10px 15px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
      }

      #contact button:hover {
        background: #0097a7;
      }

      footer {
        background: #002850;
        color: white;
        text-align: center;
        padding: 20px;
        margin-top: 40px;
      }

      footer ul {
        list-style: none;
        padding: 0;
        margin-bottom: 10px;
      }

      footer li {
        display: inline;
        margin: 0 10px;
      }

      footer a {
        text-decoration: none;
        color: #00bcd4;
      }

      footer .social img {
        width: 24px;
        margin: 0 5px;
        vertical-align: middle;
        filter: brightness(0) invert(1);
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">NigeriaTech</div>
      <nav>
        <a href="#">Home</a>
        <a href="#courses">Courses</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero" data-aos="fade-up">
      <h1>Empower Your Tech Future</h1>
      <p>Learn online, gain real-world skills & join 300,000+ students</p>
      <a href="#contact">Get Started</a>
    </section>

    <main>
      <h2 id="courses">Our Bootcamps</h2>
      <div class="cards">
        <div class="card" data-aos="fade-up">
          <h3>FullStack Developer Bootcamp</h3>
          <p>Learn to build dynamic, responsive websites & apps.</p>
          <a href="https://www.Nigeria.com/full-stack-developer-bootcamp" target="_blank">Learn More</a>
        </div>
        <div class="card" data-aos="fade-up">
          <h3>Data Science Bootcamp</h3>
          <p>Master data analytics, machine learning & visualization.</p>
          <a href="https://www.Nigeria.com/data-science-bootcamp" target="_blank">Learn More</a>
        </div>
      </div>

      <h2>Job Opportunities</h2>
      <div data-aos="fade-right">
        <h3>Frontend Developer</h3>
        <span>Remote</span>
      </div>
      <div data-aos="fade-right">
        <h3>Backend Developer</h3>
        <span>Remote</span>
      </div>
      <div data-aos="fade-right">
        <h3>Data Scientist</h3>
        <span>Jabi Abuja</span>
      </div>

      <section id="testimonials" data-aos="fade-up">
        <h2>What Our Students Say</h2>
        <blockquote>"The bootcamp gave me real skills to land my first job!" – Ada</blockquote>
        <blockquote>"Hands-on projects and great mentors." – Chinedu</blockquote>
      </section>

      <section id="newsletter" data-aos="fade-up">
        <h2>Join Our Newsletter</h2>
        <form action="#">
          <input type="email" placeholder="Enter your email" required />
          <button type="submit">Subscribe</button>
        </form>
      </section>

      <section id="contact" data-aos="fade-up">
        <h2>Contact Us</h2>
        <form action="#">
          <label for="name">Name:</label><br />
          <input type="text" id="name" name="name" required /><br /><br />
          <label for="email">Email:</label><br />
          <input type="email" id="email" name="email" required /><br /><br />
          <label for="message">Message:</label><br />
          <textarea id="message" name="message" rows="4" required></textarea><br /><br />
          <button type="submit">Send Message</button>
        </form>
      </section>
    </main>

    <footer>
      <ul>
        <li><a href="#">Courses</a></li>
        <li><a href="#">Programs</a></li>
        <li><a href="#">Youtube</a></li>
      </ul>
      <div class="social">
        <a href="#"><img src="https://cdn-icons-png.flaticon.com/512/145/145802.png" alt="Facebook" /></a>
        <a href="#"><img src="https://cdn-icons-png.flaticon.com/512/145/145812.png" alt="Twitter" /></a>
        <a href="#"><img src="https://cdn-icons-png.flaticon.com/512/145/145807.png" alt="Instagram" /></a>
      </div>
      <span>© 2025. NigeriaTech</span>
    </footer>

    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>AOS.init();</script>
  </body>
</html>
