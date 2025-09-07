<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>Sagar Patil — Portfolio</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Bootstrap Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
  <!-- Animate.css -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet"/>
  <!-- AOS -->
  <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet"/>

  <style>
    body {scroll-behavior: smooth;}
    header.hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(120deg,#0d6efd,#6610f2);
      color: white;
      text-align: center;
    }
    header.hero h1 {font-size: 3rem;}
    .section-title {font-weight: 700; margin-bottom: 1.5rem;}
    .card:hover {
      transform: translateY(-8px);
      transition: all .3s ease;
      box-shadow: 0 12px 28px rgba(0,0,0,0.15);
    }
    footer {background:#111; color:#aaa;}
    footer a {color:#fff; text-decoration:none;}
  </style>
</head>
<body>

<!-- HERO -->
<header class="hero">
  <div class="container">
    <h1 class="animate__animated animate__fadeInDown">Hi, I'm <span class="fw-bold">Sagar Patil</span></h1>
    <p class="lead animate__animated animate__fadeInUp">Aspiring Software Developer · Core Java · SQL · Web Tech</p>
    <div class="mt-4">
      <a href="#projects" class="btn btn-light btn-lg me-2"><i class="bi bi-diagram-3"></i> Projects</a>
      <a href="#contact" class="btn btn-outline-light btn-lg"><i class="bi bi-envelope"></i> Contact</a>
    </div>
  </div>
</header>

<!-- ABOUT -->
<section id="about" class="py-5">
  <div class="container" data-aos="fade-up">
    <h2 class="section-title text-center">About Me</h2>
    <p class="text-center w-75 mx-auto">Final-year Computer Engineering student with skills in Core Java, SQL, and Frontend. Passionate about IoT security and building responsive UI/UX solutions. Strong problem solver, quick learner, and team player.</p>
  </div>
</section>

<!-- SKILLS -->
<section id="skills" class="py-5 bg-light">
  <div class="container">
    <h2 class="section-title text-center">Skills</h2>
    <div class="row text-center g-4">
      <div class="col-md-3" data-aos="zoom-in">
        <i class="bi bi-code-slash fs-1 text-primary"></i>
        <h5 class="mt-2">Programming</h5>
        <p>Core Java, OOP, Swing</p>
      </div>
      <div class="col-md-3" data-aos="zoom-in" data-aos-delay="100">
        <i class="bi bi-database fs-1 text-primary"></i>
        <h5 class="mt-2">Database</h5>
        <p>SQL, Joins, Indexing</p>
      </div>
      <div class="col-md-3" data-aos="zoom-in" data-aos-delay="200">
        <i class="bi bi-window-sidebar fs-1 text-primary"></i>
        <h5 class="mt-2">Frontend</h5>
        <p>HTML, CSS, Bootstrap</p>
      </div>
      <div class="col-md-3" data-aos="zoom-in" data-aos-delay="300">
        <i class="bi bi-tools fs-1 text-primary"></i>
        <h5 class="mt-2">Tools</h5>
        <p>Eclipse, MySQL, GitHub</p>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects" class="py-5">
  <div class="container">
    <h2 class="section-title text-center">Projects</h2>
    <div class="row g-4">
      <div class="col-md-6" data-aos="fade-right">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Cyber Attack Detection (2023)</h5>
            <p class="card-text">Built a system to detect IoT cyber threats (DoS, DDoS, probing, data injection, malware) with UI in Java Swing and SQL integration.</p>
            <span class="badge bg-primary">Java</span>
            <span class="badge bg-secondary">SQL</span>
            <span class="badge bg-success">Swing</span>
          </div>
        </div>
      </div>
      <div class="col-md-6" data-aos="fade-left">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Portfolio Website (2023)</h5>
            <p class="card-text">Designed a personal portfolio with responsive layout, Bootstrap design, and project showcase.</p>
            <span class="badge bg-warning text-dark">HTML</span>
            <span class="badge bg-info text-dark">CSS</span>
            <span class="badge bg-dark">Bootstrap</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EDUCATION -->
<section id="education" class="py-5 bg-light">
  <div class="container" data-aos="fade-up">
    <h2 class="section-title text-center">Education</h2>
    <ul class="list-group list-group-flush w-75 mx-auto">
      <li class="list-group-item">B.E. Computer Engineering — Pune University (2021–2025)</li>
      <li class="list-group-item">SQL Certification — QSpiders Pune (2024)</li>
      <li class="list-group-item">Core Java Programming — Apna College</li>
      <li class="list-group-item">Web Tech (HTML, CSS, Bootstrap) — Self-Learning</li>
    </ul>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="py-5">
  <div class="container" data-aos="fade-up">
    <h2 class="section-title text-center">Contact</h2>
    <div class="row justify-content-center">
      <div class="col-md-6 text-center">
        <p><i class="bi bi-envelope me-2"></i><a href="mailto:sagardpatil03@gmail.com">sagardpatil03@gmail.com</a></p>
        <p><i class="bi bi-phone me-2"></i>+91 8055461055</p>
        <p><i class="bi bi-github me-2"></i><a href="https://github.com/YOUR_GITHUB" target="_blank">GitHub Profile</a></p>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer class="py-3 text-center">
  <small>© <span id="year"></span> Sagar Patil | Built with ❤️ using Bootstrap</small>
</footer>

<!-- Scripts -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
<script>
  AOS.init();
  document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
