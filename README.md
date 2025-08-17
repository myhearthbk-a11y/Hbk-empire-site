# Hbk-empire-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The HBK Empire</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <img src="images/swe-logo.png" alt="SWE Logo" class="logo" />
    <h1>The HBK Empire</h1>
    <p class="tagline">Where Remix Meets Power</p>
  </header>

  <main>
    <section class="intro">
      <h2>Welcome to the Empire</h2>
      <p>This is your portal to bold visuals, glowing vibes, and unapologetic creativity. Powered by SWE, driven by HBK.</p>
    </section>

    <section class="features">
      <div class="card">⚡ Glowing Design</div>
      <div class="card">🎨 Remix Culture</div>
      <div class="card">👑 HBK Legacy</div>
    </section>
  </main>

  <footer>
    <p>© 2025 The HBK Empire. Built with love, chaos, and SWE energy.</p>
  </footer>
</body>
</html>
body {
  margin: 0;
  font-family: 'Orbitron', sans-serif;
  background: linear-gradient(135deg, #000428, #004e92);
  color: #f0f0f0;
  text-align: center;
}

.logo {
  width: 120px;
  margin-top: 2rem;
}

header h1 {
  font-size: 3rem;
  margin: 0.5rem 0;
  color: #00ffff;
  text-shadow: 0 0 10px #00ffff;
}

.tagline {
  font-size: 1.2rem;
  color: #ff4081;
  text-shadow: 0 0 5px #ff4081;
}

.intro {
  padding: 2rem;
  background: rgba(0, 0, 0, 0.6);
  margin: 2rem;
  border-radius: 10px;
}

.features {
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap;
  margin: 2rem;
}

.card {
  background: #111;
  border: 2px solid #00ffff;
  padding: 1rem 2rem;
  border-radius: 8px;
  box-shadow: 0 0 10px #00ffff;
  font-weight: bold;
}

footer {
  margin-top: 3rem;
  padding: 1rem;
  background: #000;
  color: #888;
}
