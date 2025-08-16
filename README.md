<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dip 'n' Dives Beta Signup</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --sun-orange: #F8A22C;
      --rock-red: #A63B24;
      --deep-teal: #217190;
      --aqua-blue: #43B8D1;
      --sand-beige: #F6E6C5;
      --dark-brown: #2C1B12;
      --white: #ffffff;
    }

  body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: var(--sand-beige);
      color: var(--dark-brown);
      line-height: 1.6;
    }

   header {
      background-color: var(--deep-teal);
      color: var(--white);
      padding: 1.5rem 2rem;
      text-align: center;
    }

  header img {
      max-width: 220px;
      display: block;
      margin: 0 auto 1rem;
    }

  header h1 {
      margin: 0;
      font-size: 2rem;
      font-weight: 700;
    }

  header p {
      margin: 0.25rem 0 0;
      font-size: 1.1rem;
    }

   .container {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
    }

  .cta {
      background-color: var(--white);
      padding: 2rem;
      border-radius: 12px;
      text-align: center;
      margin: 2rem 0;
      border: 3px solid var(--rock-red);
    }

  .cta h2 {
      color: var(--deep-teal);
      margin-bottom: 1rem;
    }

  .cta p {
      margin-bottom: 1.5rem;
    }

   form {
      margin: 1rem 0;
    }

   input[type="text"],
    input[type="email"] {
      padding: 0.75rem;
      margin: 0.5rem;
      width: calc(50% - 1rem);
      border: 2px solid var(--deep-teal);
      border-radius: 6px;
      font-size: 1rem;
    }

  button {
      background-color: var(--sun-orange);
      color: var(--white);
      border: none;
      padding: 0.9rem 1.8rem;
      font-size: 1.1rem;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 700;
      margin-top: 1rem;
   }

   button:hover {
      background-color: var(--rock-red);
  }

  .features {
      background-color: var(--aqua-blue);
      padding: 2rem;
      border-radius: 12px;
      margin-top: 3rem;
      color: var(--dark-brown);
   }

   .features h3 {
      text-align: center;
      margin-bottom: 1rem;
      color: var(--dark-brown);
   }

   .features ul {
      list-style: none;
      padding: 0;
   }

   .features li {
      margin: 0.8rem 0;
      padding-left: 1.5rem;
      position: relative;
   }

   .features li::before {
      content: "✓";
      position: absolute;
      left: 0;
      color: var(--rock-red);
      font-weight: bold;
   }

  .about {
      background-color: var(--sun-orange);
      padding: 2rem;
      border-radius: 12px;
      margin-top: 3rem;
      color: var(--white);
   }

  .about h3 {
      margin-bottom: 1rem;
  }

  .signup {
      background-color: var(--deep-teal);
      padding: 2rem;
      border-radius: 12px;
      margin: 3rem 0;
      text-align: center;
      color: var(--white);
  }

  .signup button {
      background-color: var(--sand-beige);
      color: var(--rock-red);
   }

  .signup button:hover {
      background-color: var(--rock-red);
      color: var(--white);
   }

   footer {
      background-color: var(--dark-brown);
      color: var(--sand-beige);
      text-align: center;
      padding: 1.5rem;
      margin-top: 2rem;
  }

   footer a {
      color: var(--aqua-blue);
      text-decoration: none;
      margin: 0 0.5rem;
      font-weight: 700;
    }
  </style>
</head>
<body>
  <header>
    <img src="your-logo.png" alt="Dip 'n' Dives Logo">
    <h1>Dip ‘n’ Dives</h1>
    <p>Off The Grid, Into The Water</p>
  </header>

  <div class="container">
    <div class="cta">
      <h2>Join Our Beta Launch</h2>
      <p>Get early access to the wildest swimming spots, submitted by real adventurers like you.</p>
      
 <!-- Mailchimp Form -->
  <form action="https://YOUR_MAILCHIMP_URL" method="post" target="_blank" novalidate>
        <input type="text" name="FNAME" placeholder="First Name" required />
        <input type="email" name="EMAIL" placeholder="Email Address" required />
        <br>
        <button type="submit">Join Now →</button>
      </form>
      
  <p><small>You’ll get early access in September 2025!</small></p>
   </div>

  <div class="features">
      <h3>What You’ll Get</h3>
      <ul>
        <li>Access to our map of community-submitted “dips” and “dives”</li>
        <li>Add your own hidden spots with photos, tips & ratings</li>
        <li>Save private gems to share with trusted friends</li>
        <li>Exclusive giveaways for early users</li>
  </ul>
   </div>
   <div class="about">
      <h3>Why We Built This</h3>
      <p>We’re dippers and divers, too — and tired of overcrowded, overhyped spots. Dip ‘n’ Dives is all about keeping outdoor adventure accessible, authentic, and community-powered. Just swimming in the wild, made easy. Find your spot, swim it, rate it, pin it.</p>
  </div>

   <div class="signup">
      <h3>Stay Cool, Get Wet</h3>
      <p>Sign up and follow us for updates:</p>
      <form action="https://YOUR_MAILCHIMP_URL" method="post" target="_blank" novalidate>
        <input type="email" name="EMAIL" placeholder="Email Address" required />
        <br>
        <button type="submit">Sign Up</button>
      </form>
    </div>
  </div>

  <footer>
    <p>© 2025 Dip ‘n’ Dives</p>
    <p>
      <a href="#">Instagram</a> |
      <a href="#">Twitter</a>
    </p>
  </footer>
</body>
</html>
