<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dip 'n' Dives Beta Signup</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      /* Default: Water Theme */
      --primary: #287BA0;
      --secondary: #3ED9D4;
      --secondary-hover: #2cb7b2;
      --accent: #A6F4DC;
      --bg: #F0FAF9;
      --text: #333;
      --radius: 10px;
    }

  body.nature-theme {
      --primary: #2F5233;
      --secondary: #87C0D0;
      --secondary-hover: #6AA9B8;
      --accent: #A3B18A;
      --bg: #F9F5EC;
      --text: #333;
    }

  body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.5;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

  header {
      background-color: var(--primary);
      color: white;
      padding: 2rem 1rem;
      text-align: center;
      transition: background-color 0.3s ease;
    }

  header h1 {
      margin-bottom: 0.5rem;
    }

  main {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }

  .cta {
      background-color: var(--accent);
      padding: 1.5rem;
      border-radius: var(--radius);
      margin: 2rem 0;
      text-align: center;
      transition: background-color 0.3s ease;
    }

  form {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
      margin-top: 1rem;
    }

  label {
      display: none; /* Hidden but accessible */
    }

  input[type="text"],
    input[type="email"] {
      flex: 1 1 250px;
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }

  button {
      background-color: var(--secondary);
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.2s ease;
    }
    button:hover,
    button:focus {
      background-color: var(--secondary-hover);
    }
    .theme-toggle {
      position: absolute;
      top: 1rem;
      right: 1rem;
      background: white;
      color: var(--primary);
      border: 2px solid var(--primary);
      padding: 0.5rem 1rem;
      border-radius: 20px;
      cursor: pointer;
      font-weight: bold;
      transition: all 0.3s ease;
    }
    .theme-toggle:hover {
      background: var(--primary);
      color: white;
    }
    section {
      margin-top: 2rem;
    }
    ul {
      padding-left: 1.5rem;
    }
    .social-links {
      display: flex;
      gap: 1rem;
      margin-top: 0.5rem;
    }
    .social-links a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 700;
    }
    .social-links a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Dip ‘n’ Dives</h1>
    <p>Off The Grid and Into The Water</p>
    <button class="theme-toggle" onclick="toggleTheme()">Switch Theme</button>
  </header>

  <main>
    <section class="cta">
      <h2>Join Our Beta Launch</h2>
      <p>Get early access to the wildest swimming spots, submitted by real adventurers like you.</p>
      <!-- Mailchimp Form -->
        <form action="https://YOUR_MAILCHIMP_URL" method="post" target="_blank" novalidate>
        <label for="firstName">First Name</label>
        <input id="firstName" name="FNAME" type="text" placeholder="First Name" required>
       <label for="email">Email Address</label>
        <input id="email" name="EMAIL" type="email" placeholder="Email Address" required>

  <button type="submit">Join Now →</button>
      </form>
      <p><small>You’ll get early access in September 2025!</small></p>
    </section>
    <section class="features">
      <h3>What You’ll Get</h3>
      <ul>
        <li>Access to our map of community-submitted “dips” and “dives”</li>
        <li>Add your own hidden spots with photos, tips & ratings</li>
        <li>Save private gems to share with trusted friends</li>
        <li>Exclusive giveaways for early users</li>
      </ul>
    </section>

  <section class="about">
      <h3>Why We Built This</h3>
      <p>We’re dippers and divers too — and tired of overcrowded, overhyped spots. Dip ‘n’ Dives is all about keeping outdoor adventure accessible, authentic, and community-powered. Just swimming in the wild, made easy. Find your spot, swim it, rate it, pin it.</p>
    </section>

  <section class="social">
      <h3>Stay Cool, Get Wet</h3>
      <div class="social-links">
        <a href="#" aria-label="Instagram">Instagram</a>
        <a href="#" aria-label="Twitter">Twitter</a>
      </div>
    </section>
  </main>

  <script>
    function toggleTheme() {
      document.body.classList.toggle('nature-theme');
    }
  </script>
</body>
</html>


