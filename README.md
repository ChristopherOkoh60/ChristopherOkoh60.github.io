<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jane Doe | Software Engineer</title>
  <style>
    :root {
      --bg: #0f172a;
      --card-bg: #1e293b;
      --text: #f8fafc;
      --text-muted: #94a3b8;
      --accent: #38bdf8;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
      padding: 2rem 1rem;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
    }

    header {
      margin-bottom: 3rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      color: var(--text);
    }

    header p {
      color: var(--accent);
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }

    section {
      margin-bottom: 2.5rem;
    }

    h2 {
      font-size: 1.5rem;
      border-bottom: 2px solid var(--card-bg);
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
      color: var(--accent);
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .card {
      background-color: var(--card-bg);
      padding: 1.25rem;
      border-radius: 8px;
      transition: transform 0.2s;
    }

    .card:hover {
      transform: translateY(-4px);
    }

    .card h3 {
      margin-bottom: 0.5rem;
    }

    .card p {
      color: var(--text-muted);
      font-size: 0.95rem;
    }

    .links a {
      color: var(--accent);
      text-decoration: none;
      margin-right: 1.5rem;
      font-weight: 600;
    }

    .links a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="container">
    <header>
      <h1>Jane Doe</h1>
      <p>Computer Science Student & Full-Stack Developer</p>
    </header>

    <section id="about">
      <h2>About Me</h2>
      <p>
        Hi! I'm Jane, a computer science enthusiast building web applications, exploring AI/ML, 
        and contributing to open-source software. Welcome to my GitHub page!
      </p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="projects-grid">
        <div class="card">
          <h3>Project Alpha</h3>
          <p>A web app built with Python and JavaScript to analyze environmental sensor data.</p>
        </div>
        <div class="card">
          <h3>Project Beta</h3>
          <p>A lightweight mobile app built with React Native for tracking daily task habits.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Connect</h2>
      <div class="links">
        <a href="https://github.com/your-username" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/your-profile" target="_blank">LinkedIn</a>
        <a href="mailto:your-email@example.com">Email Me</a>
      </div>
    </section>
  </div>

</body>
</html>
