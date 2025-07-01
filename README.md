<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gigih Pambuko | Software Engineer</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <script>
    function toggleTheme() {
      document.body.classList.toggle("light-mode");
    }
  </script>
  <style>
    :root {
      --bg-dark: #0d1117;
      --text-dark: white;
      --bg-light: white;
      --text-light: #111;
    }
    body {
      background-color: var(--bg-dark);
      color: var(--text-dark);
      font-family: 'Segoe UI', sans-serif;
      transition: all 0.3s ease-in-out;
    }
    body.light-mode {
      background-color: var(--bg-light);
      color: var(--text-light);
    }
    a { color: #58a6ff; text-decoration: none; }
    a:hover { text-decoration: underline; }
    .badge-tech { margin: 2px; }
    .profile-img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 3px solid #fff;
      margin-bottom: 20px;
    }
    nav {
      position: sticky;
      top: 0;
      z-index: 1030;
      background-color: inherit;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg px-3">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">Gigih Pambuko</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#experience">Experience</a></li>
          <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
          <li class="nav-item"><button class="btn btn-sm btn-outline-light ms-3" onclick="toggleTheme()">Toggle Theme</button></li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="container py-5">
    <header class="text-center mb-5">
      <!-- Ganti URL foto berikut dengan URL gambar kamu -->
      <img src="https://github.com/gigihko/web-portofolio/blob/main/profile-image-gigihko.jpg?raw=true" alt="Gigih Pambuko" class="profile-img">
      <h1>Hi, I'm Gigih Pambuko</h1>
      <p class="lead">Full-Stack Developer passionate about clean architecture, automation, and scalability.</p>
    </header>

    <section id="about" class="mb-5">
  <h2>📍 About</h2>
  <p>
    Experienced in Full Stack Software Engineering and Data Professional work with over 3 years of experience in web development, data engineering, and process automation. Adept at building scalable backend systems using Python (Django), creating real-time dashboards, and streamlining operations through automation. Strong foundation in Python, SQL, RPA, ETL, and cloud-based data tools.
  </p>
</section>

    <section id="experience" class="mb-5">
      <h2>💼 Experience</h2>
      <p><strong>Full Stack Developer</strong> @ PT. Bank Rakyat Indonesia (Persero) Tbk</p>
      <ul>
        <li>Build & maintain internal systems using Django + React</li>
        <li>Integrate legacy systems with modern RESTful APIs</li>
        <li>Build automation for reporting & task pipelines</li>
      </ul>
    </section>

    <section id="education" class="mb-5">
      <h2>🎓 Education</h2>
      <p><strong>Universitas Gadjah Mada</strong> – Bachelor's Degree, Mathematics</p>
    </section>

    <section id="skills" class="mb-5">
      <h2>🛠 Skills</h2>
      <div>
        <span class="badge bg-secondary badge-tech">Next.js</span>
        <span class="badge bg-secondary badge-tech">Django</span>
        <span class="badge bg-secondary badge-tech">React</span>
        <span class="badge bg-secondary badge-tech">TailwindCSS</span>
        <span class="badge bg-secondary badge-tech">MSSQL</span>
        <span class="badge bg-secondary badge-tech">FastAPI</span>
        <span class="badge bg-secondary badge-tech">PostgreSQL</span>
        <span class="badge bg-secondary badge-tech">Docker</span>
        <span class="badge bg-secondary badge-tech">AWS</span>
      </div>
    </section>

    <section id="projects" class="mb-5">
      <h2>🚀 Projects</h2>
      <ul>
        <li><strong>Internal Dashboard System</strong> – Streamlines workflow of multiple departments with role-based access and analytics.</li>
        <li><strong>Automation Reporting Suite</strong> – Python & Excel-driven reporting tool for daily and monthly metrics.</li>
        <li><strong>Smart Approval Backend</strong> – Workflow automation using Django & Celery for financial approvals.</li>
      </ul>
    </section>

    <section id="contact" class="mb-5">
      <h2>📫 Contact</h2>
      <p>Feel free to reach out via <a href="https://linkedin.com/in/gigihko" target="_blank">LinkedIn</a></p>
    </section>

    <footer class="text-center mt-5">
      <small>© 2025 Gigih Pambuko. Built with 💻</small>
    </footer>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
