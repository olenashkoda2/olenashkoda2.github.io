<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Olena Shkoda — Flutter Developer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      font-family: 'Courier New', monospace;
      background-color: #121212;
      color: #ffffff;
      height: 100%;
      overflow: auto;
    }

    body::before {
      content: "";
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background-image: linear-gradient(#222 1px, transparent 1px), linear-gradient(to right, #222 1px, transparent 1px);
      background-size: 40px 40px;
      z-index: 0;
      opacity: 0.1;
    }

    .container {
      position: relative;
      z-index: 1;
      max-width: 850px;
      margin: 0 auto;
      padding: 60px 20px;
      text-align: left;
    }

    .accent-bar {
      width: 8px;
      height: 100%;
      background-color: #F2C94C;
      position: absolute;
      left: 0;
      top: 0;
    }

    h1 {
      font-size: 3em;
      margin: 0;
      font-weight: 700;
    }

    .highlight {
      background-color: #F2C94C;
      color: #121212;
      display: inline-block;
      padding: 4px 8px;
      margin-top: 12px;
      font-weight: bold;
    }

    p {
      font-size: 1.1em;
      line-height: 1.7em;
      max-width: 720px;
      margin-top: 40px;
    }

    a.button {
      background-color: #F2C94C;
      color: #121212;
      padding: 12px 28px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1em;
      display: inline-block;
      margin-top: 30px;
      transition: background 0.3s;
    }

    a.button:hover {
      background-color: #e2b834;
    }

    footer {
      margin-top: 4em;
      font-size: 0.9em;
      color: #999;
    }
  </style>
</head>
<body>
  <div class="accent-bar"></div>
  <div class="container">
    <h1>Turning Ideas Into</h1>
    <div class="highlight">Beautiful Code</div>

    <p>
      I’m <strong>Olena Shkoda</strong> — a Flutter developer focused on crafting responsive and visually impactful mobile applications. My work is rooted in strong design thinking and modern engineering practices.
    </p>

    <p>
      With a passion for clean architecture, animation, and performance optimization, I collaborate with teams and founders to build apps that feel smooth and purposeful. Firebase, REST APIs, and scalable UIs — all in a day’s work.
    </p>

    <a href="mailto:olena.shkoda2@gmail.com" class="button">Let’s Talk</a>

    <footer>© 2025 Olena Shkoda</footer>
  </div>
</body>
</html>
