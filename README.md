<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Shaji's Tech Fest Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <img src="images/hero.jpg" alt="Tech Banner" class="hero-img" />
    <div class="hero-text">
      <h1>Welcome to Shaji's Tech World</h1>
      <p>Explore ideas. Build the future.</p>
    </div>
  </header>

  <main>
    <section id="about">
      <h2>About This Project</h2>
      <p>This website is designed for the International Digital Fest 2025, created using HTML, CSS, and JavaScript.</p>
    </section>

    <section id="features">
      <h2>Key Features</h2>
      <div class="feature">
        <img src="images/feature1.jpg" alt="Feature 1" />
        <p>Responsive layout for all devices.</p>
      </div>
      <div class="feature">
        <img src="images/feature2.jpg" alt="Feature 2" />
        <p>Interactive JavaScript elements.</p>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <button onclick="showContact()">Click to Show Contact Info</button>
      <p id="contactInfo" style="display: none;">Email: shaji@example.com</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Shaji V.S. | All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
