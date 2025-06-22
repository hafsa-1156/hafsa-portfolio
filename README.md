<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hafsa's Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#"><img src="assets/images/Hafsa-designstyle-sharks-m.png" alt="logo" width="50" height="50" class="img-fluid"></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="hero d-flex align-items-center" id="home">
    <div class="container text-center text-white">
      <h1>Hello, I'm Hafsa</h1>
      <p>Mern stack developer | HTML • CSS • Bootstrap • Firebase • Javascript  • NodeJs • JQuery • expressjS • ApI's • npm • SQL • MongoDB</p>
    </div>
  </header>

  <!-- About -->
  <section id="about" class="py-5">
    <div class="container text-center">
      <h2>About Me</h2>
      <p>I'm Hafsa, a passionate and detail-oriented web developer with a focus on creating clean, responsive, and user-friendly websites. I specialize in HTML, CSS, Bootstrap, and Firebase to build modern front-end interfaces. I enjoy turning ideas into real, working products and love the process of solving problems through code. Whether it's a simple portfolio, I aim to deliver designs that not only look great but also function smoothly across all devices. I'm always eager to learn new technologies and grow with every project I work on.</p>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="bg-light py-5">
    <div class="container text-center">
      <h2>My Skills</h2>
      <div class="row mt-4">
        <div class="col-md-3">HTML5</div>
        <div class="col-md-3">CSS3</div>
        <div class="col-md-3">NodeJs</div>
        <div class="col-md-3">JavaScript</div>
        <div class="col-md-3">React.js</div>
        <div class="col-md-3">Firebase</div>
        <div class="col-md-3">Bootstrap</div>
        <div class="col-md-3">expressjS</div>
        <div class="col-md-3">RESTful APIs</div>
        <div class="col-md-3">Responsive Web Design</div>
        <div class="col-md-3">MongoDB </div>
        <div class="col-md-3">Basic CRUD Operations</div>
        <div class="col-md-3">JSON / API Handling</div>
        <div class="col-md-3">Postman (for API testing)</div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-5">
    <div class="container text-center">
      <h2>Projects</h2>
      <div class="row mt-4">
        <div class="col-md-4 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">Portfolio Website</h5>
              <p class="card-text">A responsive personal website to showcase my work.</p>
              <a href="#" class="btn btn-primary">View Live</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">Quiz App</h5>
              <p class="card-text">MCQ-based quiz app using JavaScript and Firebase.</p>
              <a href="#" class="btn btn-primary">View Live</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">To-Do List</h5>
              <p class="card-text">A basic task manager with Firebase backend.</p>
              <a href="#" class="btn btn-primary">View Live</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="bg-light py-5">
    <div class="container text-center">
      <h2>Contact Me</h2>
      <form class="mt-4 mx-auto" style="max-width: 600px;">
        <div class="mb-3">
          <input type="text" class="form-control" placeholder="Your Name" required>
        </div>
        <div class="mb-3">
          <input type="email" class="form-control" placeholder="Your Email" required>
        </div>
        <div class="mb-3">
          <textarea class="form-control" rows="4" placeholder="Your Message" required></textarea>
        </div>
        <button type="submit" class="btn btn-dark">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center text-white bg-dark py-3">  
    <p class="mb-0">© 2025 Hafsa | Web Developer</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html> 

