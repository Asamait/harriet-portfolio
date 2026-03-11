<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Harriet Asamait | IT Portfolio</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f9fc;
      color: #333;
    }
    header {
      background-color: #1f2937;
      color: #fff;
      text-align: center;
      padding: 50px 20px;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.2em;
      margin: 10px 0 0;
    }
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      text-align: center;
      color: #1f2937;
      margin-bottom: 20px;
    }
    .projects, .connect {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .card {
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      padding: 20px;
      width: 250px;
      text-align: center;
      transition: transform 0.2s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card i {
      font-size: 2em;
      color: #2563eb;
      margin-bottom: 10px;
    }
    .card h3 {
      margin: 10px 0;
      font-size: 1.2em;
    }
    .card p {
      font-size: 0.95em;
      color: #555;
    }
    .social i {
      font-size: 1.5em;
      margin-right: 10px;
      color: #2563eb;
      transition: color 0.2s;
    }
    .social i:hover {
      color: #1e40af;
    }
    footer {
      text-align: center;
      padding: 30px 20px;
      background-color: #1f2937;
      color: #fff;
    }
  </style>
</head>
<body>

  <header>
    <h1>Harriet Asamait</h1>
    <p>💻 Linux • 🌐 Networking • 🛡️ Cybersecurity • 🖥️ IT Support</p>
    <p>Welcome to my IT portfolio! Documenting my learning journey and technical projects.</p>
  </header>

  <section>
    <h2>💼 Projects</h2>
    <div class="projects">
      <div class="card">
        <i class="fa-brands fa-linux"></i>
        <h3>Linux Practice Notes</h3>
        <p>Hands-on exercises and command-line mastery for Linux systems.</p>
      </div>
      <div class="card">
        <i class="fa-solid fa-network-wired"></i>
        <h3>Networking Fundamentals Lab</h3>
        <p>Practical labs covering networking protocols and configurations.</p>
      </div>
      <div class="card">
        <i class="fa-solid fa-shield-halved"></i>
        <h3>Cybersecurity Awareness Guide</h3>
        <p>Essential tips and practices for staying secure online.</p>
      </div>
      <div class="card">
        <i class="fa-solid fa-computer"></i>
        <h3>IT Support Troubleshooting Guide</h3>
        <p>Step-by-step solutions for common IT support issues.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>🔗 Connect With Me</h2>
    <div class="connect social">
      <a href="https://github.com/Asamait" target="_blank"><i class="fa-brands fa-github"></i></a>
      <a href="https://www.linkedin.com/in/harriet-asamait-269b8736a" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
      <a href="mailto:harrietasamait5@gmail.com"><i class="fa-solid fa-envelope"></i></a>
    </div>
  </section>

  <footer>
    &copy; 2026 Harriet Asamait. All rights reserved.
  </footer>

</body>
</html>
