# portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IT Portfolio</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background:#f4f4f4;
      color:#333;
      line-height:1.6;
    }

    header{
      background:#0f172a;
      color:white;
      padding:40px 20px;
      text-align:center;
    }

    header h1{
      font-size:42px;
      margin-bottom:10px;
    }

    header p{
      font-size:18px;
    }

    nav{
      background:#1e293b;
      padding:15px;
      text-align:center;
    }

    nav a{
      color:white;
      text-decoration:none;
      margin:0 15px;
      font-weight:bold;
    }

    nav a:hover{
      color:#38bdf8;
    }

    section{
      padding:50px 20px;
      max-width:1000px;
      margin:auto;
    }

    h2{
      margin-bottom:20px;
      color:#0f172a;
      border-left:5px solid #38bdf8;
      padding-left:10px;
    }

    .skills{
      display:flex;
      flex-wrap:wrap;
      gap:10px;
    }

    .skill{
      background:#38bdf8;
      color:white;
      padding:10px 15px;
      border-radius:20px;
    }

    .project-card{
      background:white;
      padding:20px;
      margin-bottom:20px;
      border-radius:10px;
      box-shadow:0 2px 8px rgba(0,0,0,0.1);
    }

    .project-card h3{
      margin-bottom:10px;
      color:#0f172a;
    }

    .contact p{
      margin-bottom:10px;
    }

    footer{
      background:#0f172a;
      color:white;
      text-align:center;
      padding:20px;
      margin-top:30px;
    }

    .btn{
      display:inline-block;
      margin-top:15px;
      padding:10px 20px;
      background:#38bdf8;
      color:white;
      text-decoration:none;
      border-radius:5px;
    }

    .btn:hover{
      background:#0284c7;
    }
  </style>
</head>

<body>

  <!-- Header -->
  <header>
    <h1>Your Name</h1>
    <p>Aspiring IT Professional | Web Developer | Programmer</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I am an IT student passionate about web development,
      programming, and building creative projects.
      I enjoy learning modern technologies and solving real-world problems.
    </p>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>

    <div class="skills">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Python</div>
      <div class="skill">Java</div>
      <div class="skill">MySQL</div>
      <div class="skill">GitHub</div>
      <div class="skill">React</div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>Projects</h2>

    <div class="project-card">
      <h3>Student Management System</h3>
      <p>
        Developed a system to manage student records,
        attendance, and marks using Python and MySQL.
      </p>
    </div>

    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>
        Created a responsive personal portfolio website
        using HTML, CSS, and JavaScript.
      </p>
    </div>

    <div class="project-card">
      <h3>Weather App</h3>
      <p>
        Built a weather forecasting application using API integration.
      </p>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2>Contact</h2>

    <p>📧 Email: yourname@email.com</p>
    <p>📱 Phone: +91 XXXXX XXXXX</p>
    <p>🔗 LinkedIn: linkedin.com/in/yourname</p>
    <p>💻 GitHub: github.com/yourname</p>

    <a href="#" class="btn">Download Resume</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 Your Name | IT Portfolio</p>
  </footer>

</body>
</html>