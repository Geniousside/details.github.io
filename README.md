<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
      <div class="hero-text">
        <h1>Hello, I'm Om Krishna Rai</h1>
        <p>A Full Stack Web Developer</p>
        <a href="#contact" class="btn">Contact Me</a>
      </div>
    </header>

    <main>
      <section id="about">
        <h2>About Me</h2>
        <img src="profile-pic.jpg" alt="Profile Picture" />
        <p>
          Hi, my name is Om Krishna Rai and I'm a full stack web developer with over 5
          years of experience. I specialize in building modern and responsive
          websites and applications using HTML, CSS, JavaScript, and other web
          technologies.
        </p>
      </section>

      <section id="skills">
        <h2>My Skills</h2>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>React</li>
          <li>Node.js</li>
          <li>Express</li>
          <li>MySQL</li>
          <li>MongoDB</li>
        </ul>
      </section>

      <section id="projects">
        <h2>My Projects</h2>
        <div class="project">
          <img src="project-1.jpg" alt="Project 1" />
          <h3>Project 1</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#" class="btn">View Project</a>
        </div>
        <div class="project">
          <img src="project-2.jpg" alt="Project 2" />
          <h3>Project 2</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#" class="btn">View Project</a>
        </div>
        <div class="project">
          <img src="project-3.jpg" alt="Project 3" />
          <h3>Project 3</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#" class="btn">View Project</a>
        </div>
      </section>

      <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="POST">
          <label for="name">Name</label>
          <input type="text" id="name" name="name" required />
          <label for="email">Email</label>
          <input type="email" id="email" name="email" required />
          <label for="message">Message</
