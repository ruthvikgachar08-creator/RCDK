<!-- Replace your old nav bar with this in ALL your HTML files -->
<header>
  <nav>
    <a href="index.html" class="logo">RCDK</a>
    <ul class="nav-links">
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="projects.html">Projects</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
</header>
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
