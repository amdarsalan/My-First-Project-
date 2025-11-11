<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title> My Portfolio </title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <nav>
      <div class="logo">MyPortfolio</div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <div class="burger">&#9776;</div>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Hello, I'm Md </h1>
    <p>Web Developer | Designer | Coder</p>
    <a href="#contact" class="btn">Hire Me</a>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate front-end developer with experience in building responsive websites using HTML, CSS, and JavaScript.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills-container">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">React</div>
      <div class="skill">Bootstrap</div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects-grid">
      <div class="project-card">Project 1</div>
      <div class="project-card">Project 2</div>
      <div class="project-card">Project 3</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form id="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p id="form-message"></p>
  </section>

  <footer>
    <p>&copy; 2025 Md. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
