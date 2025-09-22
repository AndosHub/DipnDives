<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dip 'n' Dives - Join the Beta</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

   body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background-color: #F6E6C5;
            color: #2C1B12;
            line-height: 1.6;
        }
    .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
    /* Header */
        .header {
            padding: 20px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

  .logo {
            height: 60px;
            width: auto;
        }

   .join-beta-btn {
            background-color: #F8A22C;
            color: #2C1B12;
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s ease;
        }

   .join-beta-btn:hover {
            background-color: #e6921a;
            transform: translateY(-2px);
        }

   /* Hero Section */
        .hero {
            text-align: center;
            padding: 80px 0;
        }

   .hero h1 {
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 20px;
            color: #2C1B12;
        }

   .hero .highlight {
            color: #217190;
        }
      .hero p {
            font-size: 1.2rem;
            margin-bottom: 40px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            color: #A63B24;
        }
    /* Signup Form */
        .signup-form {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            max-width: 500px;
            margin: 0 auto;
            border: 2px solid #43B8D1;
        }
    .signup-form h3 {
            color: #217190;
            margin-bottom: 10px;
            font-size: 1.3rem;
        }
    .signup-form p {
            color: #666;
            margin-bottom: 20px;
            font-size: 0.9rem;
        }

   .form-group {
            display: flex;
            gap: 10px;
            margin-bottom: 15px;
        }
       .form-input {
           flex: 1;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
        }
    .submit-btn {
            background-color: #217190;
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }

  .submit-btn:hover {
            background-color: #1a5a73;
        }

   .form-footer {
            font-size: 0.8rem;
            color: #666;
            text-align: center;
            margin-top: 15px;
        }
    /* Features Section */
        .features {
            padding: 80px 0;
            text-align: center;
        }
    .features h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #2C1B12;
        }   
  .features-subtitle {
            color: #A63B24;
            margin-bottom: 50px;
            font-size: 1.1rem;
        }

   .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }

   .feature-card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            border: 2px solid #43B8D1;
            transition: transform 0.3s ease;
        }

   .feature-card:hover {
            transform: translateY(-5px);
        }

   .feature-icon {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: #217190;
        }

   .feature-card h3 {
            color: #2C1B12;
            margin-bottom: 15px;
            font-size: 1.3rem;
        }

   .feature-card p {
            color: #666;
            font-size: 0.95rem;
        }

  /* CTA Section */
        .cta-section {
            background: linear-gradient(135deg, #43B8D1 0%, #F8A22C 100%);
            padding: 80px 0;
            text-align: center;
            color: white;
        }

   .cta-section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            /* Ensuring proper contrast for white text on gradient background */
            color: #ffffff;
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }

   .cta-section p {
            font-size: 1.2rem;
            margin-bottom: 40px;
            /* Ensuring proper contrast for white text on gradient background */
            color: #ffffff;
            text-shadow: 0 1px 2px rgba(0,0,0,0.3);
        }

  .cta-form {
            background: white;
            padding: 25px;
            border-radius: 15px;
            max-width: 500px;
            margin: 0 auto;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

  .cta-form .form-group {
            margin-bottom: 20px;
        }

   .cta-submit {
            background-color: #F8A22C;
            color: #2C1B12;
            width: 100%;
            padding: 15px;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }

   .cta-submit:hover {
            background-color: #e6921a;
        }

   /* Footer */
        .footer {
            background-color: #2C1B12;
            color: white;
            padding: 40px 0;
            text-align: center;
        }
.footer-logo {
            height: 40px;
            margin-bottom: 20px;
            filter: brightness(0) invert(1);
        }

  .footer p {
            /* Ensuring proper contrast for footer text */
            color: #ffffff;
            font-size: 0.9rem;
        }

   /* Responsive */
        @media (max-width: 768px) {
            .header {
                flex-direction: column;
                gap: 20px;
            }

   .hero h1 {
                font-size: 2.5rem;
            }

   .form-group {
                flex-direction: column;
            }

   .features-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="container">
            <div class="header">
                <img src="/logo.png" alt="Dip 'n' Dives" class="logo">
                <a href="#signup" class="join-beta-btn">Join the Beta</a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
 <section class="hero">
        <div class="container">
            <h1>Dive Into <span class="highlight">Adventure</span></h1>
            <p>Join the beta community of outdoor enthusiasts discovering hidden swimming spots, secret diving locations, and off-the-beaten-path aquatic adventures.</p>
            
   <div class="signup-form" id="signup">
                <h3>🏊 Get Early Access</h3>
                <p>Be the first to explore when we launch this beta.</p>
                <form>
                    <div class="form-group">
                        <input type="email" class="form-input" placeholder="Your email address" required>
                        <button type="submit" class="submit-btn">Join Beta</button>
                    </div>
                    <div class="form-footer">
                        ✓ Get adventure alerts  ✓ Launch updates
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Features Section -->
 <section class="features">
        <div class="container">
            <h2>What Awaits You</h2>
            <p class="features-subtitle">Beta access includes exclusive features for the ultimate aquatic adventure experience.</p>
            
   <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">📍</div>
                    <h3>Hidden Locations</h3>
                    <p>Discover secret swimming holes and diving spots known only to locals and adventure seekers.</p>
                </div>
                
   <div class="feature-card">
                    <div class="feature-icon">🤝</div>
                    <h3>Adventure Community</h3>
                    <p>Connect with fellow water enthusiasts and share your favorite off-the-grid discoveries.</p>
                </div>
                
   <div class="feature-card">
                    <div class="feature-icon">🛡️</div>
                    <h3>Safety First</h3>
                    <p>Real-time conditions, safety ratings, and emergency contact for every aquatic location.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
  <section class="cta-section">
        <div class="container">
            <h2>Ready to Make a Splash?</h2>
            <p>Join thousands of adventurers already signed up for exclusive beta access.</p>
            
  <div class="cta-form">
                <form>
                    <div class="form-group">
                        <input type="email" class="form-input" placeholder="Your adventure starts here..." required>
                    </div>
                    <button type="submit" class="cta-submit">Dive In 🏊</button>
                    <div class="form-footer">
                        🔒 We won't send spam. Unsubscribe anytime.
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
   <footer class="footer">
        <div class="container">
            <img src="/logo.png" alt="Dip 'n' Dives" class="footer-logo">
            <p>© 2024 Dip 'n' Dives. Beta launching soon.</p>
        </div>
    </footer>

   <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });  
   // Form submission handling
        document.querySelectorAll('form').forEach(form => {
            form.addEventListener('submit', function(e) {
                e.preventDefault();
                const email = this.querySelector('input[type="email"]').value;
                if (email) {
                    alert('Thanks for joining the beta! We\'ll be in touch soon.');
                    this.querySelector('input[type="email"]').value = '';
                }
            });
        });
    </script>
</body>
</html>
