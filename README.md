<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Modern GitHub Page</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: #333;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      padding: 2rem;
      text-align: center;
      color: white;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      opacity: 0.9;
    }

    .container {
      background: white;
      max-width: 900px;
      margin: 2rem auto;
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.15);
      text-align: center;
    }

    .buttons {
      margin-top: 1.5rem;
    }

    button {
      padding: 0.8rem 1.5rem;
      border: none;
      background: #667eea;
      color: white;
      border-radius: 999px;
      font-size: 1rem;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    button:hover {
      background: #5a67d8;
      transform: translateY(-2px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }

    .card {
      padding: 1.5rem;
      border-radius: 15px;
      background: #f9fafb;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    footer {
      margin-top: auto;
      text-align: center;
      padding: 1rem;
      color: white;
      opacity: 0.8;
    }
  </style>
</head>
<body>

<header>
  <h1>✨ My Modern Website</h1>
  <p>Built with GitHub Pages</p>
</header>

<div class="container">
  <h2>Hello there 👋</h2>
  <p>This is a clean, modern landing page you can customize.</p>

  <div class="buttons">
    <button onclick="sayHello()">Say Hello</button>
  </div>

  <div class="card-grid">
    <div class="card">
      <h3>🚀 Projects</h3>
      <p>Showcase your work here.</p>
    </div>
    <div class="card">
      <h3>📄 About</h3>
      <p>Tell people who you are.</p>
    </div>
    <div class="card">
      <h3>📬 Contact</h3>
      <p>Let people reach out.</p>
    </div>
  </div>
</div>

<footer>
  <p>© 2026 My Website</p>
</footer>

<script>
  function sayHello() {
    alert('Hey! Welcome to my modern GitHub page 😄');
  }
</script>

</body>
</html>
