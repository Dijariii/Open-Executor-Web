<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Open Source Softworks</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: #f0f0f0;
    }

    header {
      background-color: #1f1f1f;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #a0a0a0;
    }

    nav {
      background-color: #151515;
      display: flex;
      justify-content: center;
      padding: 1rem;
    }

    nav a {
      margin: 0 1rem;
      color: #00d9ff;
      text-decoration: none;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .features, .about, .download, .contact {
      margin-bottom: 3rem;
    }

    h2 {
      border-bottom: 2px solid #00d9ff;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }

    ul {
      list-style-type: square;
      padding-left: 1.5rem;
    }

    footer {
      background-color: #1f1f1f;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #888;
    }

    .button {
      display: inline-block;
      background-color: #00d9ff;
      color: #000;
      padding: 0.75rem 1.5rem;
      margin-top: 1rem;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }

    .button:hover {
      background-color: #00b8d9;
    }
  </style>
</head>
<body>
  <header>
    <h1>Open Source Softworks</h1>
    <p>A powerful, open-source Roblox executor made for developers and enthusiasts.</p>
  </header>

  <nav>
    <a href="#features">Features</a>
    <a href="#about">About</a>
    <a href="#download">Download</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="features" id="features">
    <h2>🔧 Features</h2>
    <ul>
      <li>Fully open-source executor built with performance in mind</li>
      <li>Modern and clean UI with dark mode</li>
      <li>Supports multiple script types and APIs</li>
      <li>Script hub integration with popular Roblox scripts</li>
      <li>Auto-updater and plugin support</li>
      <li>Security-first design with sandbox execution</li>
      <li>Advanced debugging tools for script developers</li>
    </ul>
  </section>

  <section class="about" id="about">
    <h2>📖 About</h2>
    <p>
      Open Source Softworks is a community-driven Roblox executor focused on transparency,
      customization, and reliability. We believe in empowering users and developers
      with tools that are free, powerful, and safe. Unlike traditional executors, OSS
      is fully open for inspection and improvement by anyone.
    </p>
    <p>
      Built with a TypeScript frontend and Python backend, OSS blends performance and flexibility. 
      Whether you're a scripter, developer, or casual user, Open Source Softworks provides 
      everything you need to explore and build within Roblox like never before.
    </p>
  </section>

  <section class="download" id="download">
    <h2>⬇️ Download</h2>
    <p>
      You can download the latest version of Open Source Softworks from our GitHub releases page.
      The app is available for Windows and Linux (via Wine). Please read the installation guide before use.
    </p>
    <a class="button" href="https://github.com/yourusername/opensourcesoftworks/releases">Download Now</a>
  </section>

  <section class="contact" id="contact">
    <h2>📬 Contact</h2>
    <p>
      Have a question, suggestion, or found a bug? Reach out to us via:
    </p>
    <ul>
      <li>GitHub Issues: <a href="https://github.com/yourusername/opensourcesoftworks/issues" style="color: #00d9ff;">Submit here</a></li>
      <li>Email: <a href="mailto:contact@oss.dev" style="color: #00d9ff;">contact@oss.dev</a></li>
      <li>Discord: <strong>Coming soon</strong></li>
    </ul>
  </section>

  <footer>
    &copy; 2025 Open Source Softworks. Built with ❤️ for the Roblox community.
  </footer>
</body>
</html>
