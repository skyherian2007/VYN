                                                      nano index.html
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VyNxSky Portfolio</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Navigation -->
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- Hero Section -->
<section id="home" class="hero">
  <img src="https://raw.githubusercontent.com/NdikzDatabase/Database/main/Database/1755612684556-1lmqsu.jpg" alt="Avatar">
  <h1>Welcome To VyNxSky Portfolio</h1>
  <p>Explore my work and skills</p>
</section>

<!-- About Section -->
<section id="about">
  <h2>About Me</h2>
  <p>Hello! I’m VyNxSky, a passionate developer and designer creating modern websites and projects. I love building interactive and responsive websites.</p>
</section>

<!-- Skills Section -->
<section id="skills">
  <h2>Skills</h2>
  <div class="skills-container">
    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">JavaScript</div>
    <div class="skill">Python</div>
    <div class="skill">React</div>
  </div>
</section>

<!-- Projects Section -->
<section id="projects">
  <h2>Projects</h2>
  <div class="projects-container">
    <div class="project">Project 1</div>
    <div class="project">Project 2</div>
    <div class="project">Project 3</div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact">
  <h2>Contact</h2>
  <p>Email: example@vynxsky.com</p>
  <p>Phone: +62 812 3456 7890</p>
  <div class="social">
    <a href="#">Instagram</a>
    <a href="#">GitHub</a>
    <a href="#">LinkedIn</a>
  </div>
</section>

</body>
</html>

                                                      nano style.css
/* Reset & basic */
body, html {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    scroll-behavior: smooth;
}

/* Navigation */
nav {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(0,0,0,0.7);
    z-index: 100;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 10px 0;
    margin: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #00bfa5;
}

/* Hero Section */
.hero {
    height: 100vh;
    background: url('https://raw.githubusercontent.com/NdikzDatabase/Database/main/Database/1755612711971-5jl9vx.jpg') no-repeat center center;
    background-size: cover;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.hero img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin-bottom: 20px;
    object-fit: cover;
    border: 4px solid white;
}

.hero h1 {
    font-size: 50px;
    margin: 0;
    text-shadow: 2px 2px 10px rgba(0,0,0,0.7);
}

.hero p {
    font-size: 24px;
    text-shadow: 1px 1px 5px rgba(0,0,0,0.7);
}

/* Sections */
section {
    padding: 80px 20px;
    text-align: center;
}

section h2 {
    font-size: 40px;
    margin-bottom: 20px;
}

/* Skills */
.skills-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
}

.skill {
    background: #00bfa5;
    padding: 15px 25px;
    border-radius: 10px;
    color: white;
    font-weight: bold;
    transition: transform 0.3s;
}

.skill:hover {
    transform: scale(1.1);
}

/* Projects */
.projects-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
}

.project {
    background: #00796b;
    color: white;
    padding: 25px;
    border-radius: 15px;
    width: 200px;
    transition: transform 0.3s;
}

.project:hover {
    transform: scale(1.05);
}

/* Contact */
.social a {
    display: inline-block;
    margin: 10px;
    text-decoration: none;
    color: #00bfa5;
    font-weight: bold;
    transition: color 0.3s;
}

.social a:hover {
    color: #004d40;
}
