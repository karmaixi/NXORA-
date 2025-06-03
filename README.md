<!DOCTYPE html><html lang="en"><head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NXora</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f9f9f9;
      color: #1a1a1a;
    }header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.logo {
  display: flex;
  align-items: center;
}

.logo img {
  height: 40px;
  margin-right: 10px;
}

nav a {
  margin-left: 1rem;
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

nav a:hover {
  color: #0070f3;
}

.hero {
  padding: 4rem 2rem;
  text-align: center;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
  color: #555;
  margin-bottom: 2rem;
}

.cta-button {
  padding: 0.75rem 1.5rem;
  background-color: #0070f3;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 1rem;
  cursor: pointer;
}

.cta-button:hover {
  background-color: #005ac1;
}

footer {
  text-align: center;
  padding: 2rem;
  background-color: #fff;
  font-size: 0.9rem;
  color: #777;
  margin-top: 2rem;
}

@media (max-width: 768px) {
  header {
    flex-direction: column;
    align-items: flex-start;
  }

  nav {
    display: flex;
    flex-direction: column;
    width: 100%;
    margin-top: 1rem;
  }

  nav a {
    margin: 0.5rem 0;
  }

  .hero h1 {
    font-size: 2rem;
  }

  .hero p {
    font-size: 1rem;
  }
}

  </style>
</head><body>
  <header>
    <div class="logo">
      <img src="NXora_logo.png" alt="NXora Logo">
      <span><strong>NXora</strong></span>
    </div>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Services</a>
      <a href="#">Contact</a>
    </nav>
  </header>  <section class="hero">
    <h1>Welcome to NXora</h1>
    <p>Empowering Innovation Through Digital Excellence</p>
    <button class="cta-button">Get Started</button>
  </section>  <footer>
    &copy; 2025 NXora. All rights reserved.
  </footer>
</body></html>
