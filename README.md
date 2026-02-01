
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nighthawk Digital Media</title>

  <!-- Google Icons -->
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background-color: #0b0f1a;
      color: #f5f7fa;
      line-height: 1.6;
    }

    /* HERO */
    header {
      background:
        linear-gradient(rgba(11,15,26,0.85), rgba(11,15,26,0.95)),
        url("https://images.unsplash.com/photo-1546182990-dffeafbe841d");
      background-size: cover;
      background-position: center;
      padding: 90px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3.2rem;
      letter-spacing: 3px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.3rem;
      color: #cbd5f5;
      max-width: 700px;
      margin: auto;
    }

    section {
      padding: 70px 20px;
      max-width: 1100px;
      margin: auto;
    }

    h2 {
      color: #8ab4ff;
      margin-bottom: 20px;
      font-size: 2.2rem;
      text-align: center;
    }

    /* SERVICES */
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 40px;
    }

    .card {
      background: #141b2d;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 30px rgba(0,0,0,0.4);
      text-align: center;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    .material-icons {
      font-size: 48px;
      color: #3b82f6;
      margin-bottom: 15px;
    }

    .card h3 {
      margin-top: 10px;
      margin-bottom: 10px;
      color: #ffffff;
    }

    .card p {
      color: #cbd5f5;
      font-size: 0.95rem;
    }

    /* CTA */
    .cta {
      background:
        linear-gradient(rgba(15,23,42,0.9), rgba(15,23,42,0.9)),
        url("https://images.unsplash.com/photo-1519681393784-d120267933ba");
      background-size: cover;
      background-position: center;
      text-align: center;
      padding: 80px 20px;
      border-radius: 20px;
    }

    .cta h2 {
      margin-bottom: 15px;
    }

    .cta p {
      max-width: 700px;
      margin: auto auto 30px;
    }

    .cta a {
      display: inline-block;
      background: #3b82f6;
      color: #ffffff;
      padding: 16px 35px;
      border-radius: 40px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1rem;
      transition: background 0.3s;
    }

    .cta a:hover {
      background: #2563eb;
    }

    footer {
      background: #020617;
      text-align: center;
      padding: 25px;
      font-size: 0.9rem;
      color: #94a3b8;
      margin-top: 60px;
    }
  </style>
</head>

<body>

<header>
  <h1>NIGHTHAWK DIGITAL MEDIA</h1>
  <p>We hunt down outdated information, clean up your online presence, and keep your business sharp, accurate, and trusted.</p>
</header>

<section>
  <h2>What We Do</h2>
  <p style="text-align:center; max-width:800px; margin:auto;">
    Your customers search before they buy. We make sure what they find is accurate,
    consistent, and working to attract more business—not costing you sales.
  </p>

  <div class="services">
    <div class="card">
      <span class="material-icons">language</span>
      <h3>Website Cleanup</h3>
      <p>We review and update existing websites to remove outdated content and improve clarity and credibility.</p>
    </div>

    <div class="card">
      <span class="material-icons">star_rate</span>
      <h3>Google Reviews & Listings</h3>
      <p>Audit and manage Google Business profiles to keep information accurate and customer-ready.</p>
    </div>

    <div class="card">
      <span class="material-icons">groups</span>
      <h3>Social Media Management</h3>
      <p>Clean up old posts, fix incorrect details, and align profiles with your current brand.</p>
    </div>

    <div class="card">
      <span class="material-icons">visibility</span>
      <h3>Reputation Monitoring</h3>
      <p>Ongoing monitoring to ensure your business stays relevant, visible, and trustworthy.</p>
    </div>
  </div>
</section>

<section class="cta">
  <h2>Turn Searches Into Customers</h2>
  <p>
    Outdated information drives customers away. Let Nighthawk Digital Media keep your
    online presence clean, consistent, and profitable.
  </p>
  <a href="mailto:youremail@example.com">Get Started</a>
</section>

<footer>
  © 2026 Nighthawk Digital Media • Built to keep your business ahead of the hunt
</footer>

</body>
</html>
