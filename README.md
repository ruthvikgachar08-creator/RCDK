<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RCDK | Official Website</title>
  <style>
    /* Clean, modern design styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    
    body {
      background-color: #f4f7f6;
      color: #333;
      line-height: 1.6;
    }

    /* Navigation Bar */
    header {
      background-color: #1a252f;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    nav {
      max-width: 1100px;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
    }

    .logo {
      color: #ffffff;
      font-size: 1.5rem;
      font-weight: bold;
      text-decoration: none;
      letter-spacing: 1px;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }

    .nav-links a {
      color: #ecf0f1;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    .nav-links a:hover, .nav-links a.active {
      color: #3498db;
    }

    /* Hero Banner Section */
    .hero {
      background: linear-gradient(135deg, #2c3e50, #3498db);
      color: white;
      text-align: center;
      padding: 4rem 1rem;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    .hero p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    /* Main Content Container */
    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1.5rem;
    }

    .card {
      background: white;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.05);
      margin-bottom: 2rem;
    }

    .card h2 {
      color: #2c3e50;
      margin-bottom: 1rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 1.5rem;
      background: #1a252f;
      color: #7f8c8d;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar with Tabs -->
  <header>
    <nav>
      <a href="#home" class="logo">RCDK</a>
      <ul class="nav-links">
        <li><a href="#home" class="active">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <h1>Welcome to RCDK</h1>
    <p>Official Hub & Digital Workspace</p>
  </section>

  <!-- Main Content Areas -->
  <div class="container">
    <div id="about" class="card">
      <h2>About RCDK</h2>
      <p>This is your official website home page. You can customize this section to introduce your project, app, or workspace.</p>
    </div>

    <div id="projects" class="card">
      <h2>Featured Projects</h2>
      <p>Showcase your builds, scripts, apps, or media content right here.</p>
    </div>

    <div id="contact" class="card">
      <h2>Get in Touch</h2>
      <p>Add your contact details, social links, or channel references here.</p>
    </div>
  </div>

  <footer>
    <p>&copy; 2026 RCDK. All rights reserved.</p>
  </footer>

</body>
</html>
