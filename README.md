<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bonace Ombati | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f7f9fc;
      color: #333;
    }
    header {
      background: #1e1e2f;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    section {
      padding: 2rem 5%;
      max-width: 1000px;
      margin: auto;
    }
    h1, h2 {
      margin: 0.5rem 0;
    }
    .projects, .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .project-card, .skill-icon {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .skill-icon img {
      width: 50px;
      height: 50px;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 0.8rem;
    }
    input, textarea, button {
      padding: 0.8rem;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      background: #1e1e2f;
      color: white;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h1>Bonace Ombati</h1>
    <p>Front-End Web Developer | IT Student at Kibabii University</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>Hello! I'm Bonace, a passionate front-end developer currently pursuing a BSc in Information Technology. I love building user-friendly, accessible web experiences and continuously improving my coding skills.</p>
  </section>

  <section>
    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Weather App</h3>
        <p>A web app that shows live weather data using OpenWeather API.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project-card">
        <h3>Todo List</h3>
        <p>A simple task manager built with vanilla JS.</p>
        <a href="#">View Project</a>
      </div>
    </div>
  </section>

  <section>
    <h2>Skills</h2>
    <div class="skills-grid">
      <div class="skill-icon"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML" /></div>
      <div class="skill-icon"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS" /></div>
      <div class="skill-icon"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" /></div>
    </div>
  </section>

  <section>
    <h2>Contact Me</h2>
    <form action="mailto:ombatibonace@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" placeholder="Your Message" rows="5"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

</body>
</html>
