<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Geramae Rotone - Stitch Fan</title>
  <style>
    /* General Styles */
    body {
      margin: 0;
      font-family: 'Comic Sans MS', Arial, sans-serif;
      background: #a0e7ff; /* Stitch sky blue background */
      color: #003366; /* Dark blue for text */
    }

    /* Header */
    header {
      background: url('https://upload.wikimedia.org/wikipedia/en/3/3c/Stitch.png') no-repeat center/contain;
      background-color: #6fcf97; /* tropical green behind image */
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    header h1 {
      font-size: 3em;
      text-shadow: 2px 2px 4px #000000;
    }

    header p {
      font-size: 1.2em;
      font-style: italic;
    }

    /* Navigation */
    nav {
      display: flex;
      justify-content: center;
      background: #003366;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 15px 20px;
      transition: 0.3s;
    }

    nav a:hover {
      background: #00cfff; /* playful Stitch blue */
    }

    /* Sections */
    section {
      padding: 50px 20px;
      text-align: center;
    }

    /* Skills / Haki */
    .skills-bar {
      background: #ddd;
      border-radius: 25px;
      margin: 10px auto;
      width: 60%;
      height: 25px;
      overflow: hidden;
    }

    .skills-fill {
      background: linear-gradient(to right, #00cfff, #0059b3);
      height: 100%;
      width: 0;
      text-align: right;
      padding-right: 10px;
      color: white;
      line-height: 25px;
      transition: width 2s ease;
    }

    /* Footer */
    footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 15px;
    }

    /* Profile image styling */
    #about img {
      border-radius: 50%;
      margin-top: 20px;
      border: 4px solid #00cfff;
    }

  </style>
</head>
<body>

  <!-- Header -->
  <header id="home">
    <h1>Geramae Rotone</h1>
    <p>“Ohana means family. Family means nobody gets left behind!”</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h2>Galactic Adventurer</h2>
    <p>Hi! I’m Geramae Rotone, a playful dreamer inspired by Stitch. I love creativity, coding, and having fun exploring new adventures in web development!</p>
    <img src="https://upload.wikimedia.org/wikipedia/en/3/3c/Stitch.png" alt="Profile" width="200">
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>My Alien Powers</h2>
    <p>Here are some of my abilities</p>
    <div class="skills-bar"><div class="skills-fill" data-skill="90%">Tech Savvy</div></div>
    <div class="skills-bar"><div class="skills-fill" data-skill="80%">Creative Mind</div></div>
    <div class="skills-bar"><div class="skills-fill" data-skill="95%">Problem Solving</div></div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:geramaerotone@example.com">geramaerotone@example.com</a></p>
    <p>“Let’s explore the galaxy of creativity together!”</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Made with 🌺 Stitch Spirit</p>
  </footer>

  <script>
    // Animate skill bars on scroll
    window.addEventListener("scroll", function(){
      let skills = document.querySelectorAll(".skills-fill");
      skills.forEach(skill => {
        let rect = skill.getBoundingClientRect();
        if(rect.top < window.innerHeight){
          skill.style.width = skill.getAttribute("data-skill");
        }
      });
    });
  </script>

</body>
</html>
