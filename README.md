<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matanao 21st Legislative Council</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff;
      color: #333;
    }
    header {
      background-color: maroon;
      color: white;
      padding: 1rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 60px;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .main-button {
      background-color: darkorange;
      color: white;
      padding: 1rem;
      border: none;
      font-size: 1.2rem;
      cursor: pointer;
      margin: 1rem auto;
      display: block;
      border-radius: 8px;
    }
    section {
      padding: 2rem;
    }
    .section-title {
      color: maroon;
      border-bottom: 2px solid darkorange;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }
    .card {
      background-color: #f9f9f9;
      padding: 1rem;
      margin: 1rem 0;
      border-left: 5px solid maroon;
      border-radius: 5px;
    }
    footer {
      background-color: maroon;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="Untitled design.png" alt="Matanao Council Logo">
    <nav>
      <a href="#news">News</a>
      <a href="#ordinances">Ordinances</a>
      <a href="#updates">Latest Update</a>
      <a href="#resolutions">Resolutions</a>
    </nav>
  </header>

  <button class="main-button" onclick="alert('Feature coming soon!')">View All Ordinances & Resolutions</button>

  <section id="news">
    <h2 class="section-title">News</h2>
    <div class="card">No recent news yet. Stay tuned for updates.</div>
  </section>

  <section id="ordinances">
  <h2 class="section-title">Ordinances</h2>
  <div class="card">
    <a href="Ordinance-001.pdf" target="_blank">Ordinance No. 001 - Waste Management Act (PDF)</a>
  </div>
</section>

  <section id="updates">
    <h2 class="section-title">Latest Update</h2>
    <div class="card">Council meeting scheduled on August 5, 2025 at 9:00 AM.</div>
  </section>

  <section id="resolutions">
    <h2 class="section-title">Resolutions</h2>
    <div class="card">Brgy Lower Marber - Support for Local Farmers</div>
  </section>

  <footer>
    &copy; 2025 Matanao 21st Legislative Council. All rights reserved.
  </footer>
</body>
</html>
