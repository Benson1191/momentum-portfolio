# momentum-portfolio
My Shopify Portfolio Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Momentum Team | Shopify Expert Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet"/>
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #ffffff;
      color: #111;
    }
    header {
      background: #0d0d0d;
      color: white;
      padding: 3rem 1.5rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1.2rem;
      opacity: 0.85;
    }
    .portfolio {
      padding: 3rem 1.5rem;
      max-width: 1100px;
      margin: auto;
    }
    .portfolio h2 {
      font-size: 2rem;
      margin-bottom: 2rem;
      text-align: center;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .project {
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 1rem;
      text-align: center;
    }
    .project a {
      color: #0077ff;
      text-decoration: none;
      font-weight: bold;
    }
    .services {
      background: #f9f9f9;
      padding: 3rem 1.5rem;
      text-align: center;
    }
    .services h2 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
    }
    .services ul {
      list-style: none;
      padding: 0;
      font-size: 1.1rem;
      line-height: 2rem;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 2rem 1.5rem;
      margin-top: 3rem;
    }
    .cta {
      background: #0077ff;
      color: white;
      display: inline-block;
      padding: 1rem 2rem;
      margin-top: 2rem;
      border-radius: 6px;
      text-decoration: none;
      font-weight: 600;
    }
  </style>
</head>
<body>

  <header>
    <h1>Momentum Team</h1>
    <p>Driving real results through data-driven Shopify solutions and growth strategy.</p>
  </header>

  <section class="portfolio">
    <h2>Live Portfolio</h2>
    <div class="projects">
      <div class="project">
        <h3>Deluni Jewels</h3>
        <a href="https://delunijewels.com" target="_blank">Visit Site</a>
      </div>
      <div class="project">
        <h3>Frugal Finds Galore</h3>
        <a href="https://frugalfindsgalore.com" target="_blank">Visit Site</a>
      </div>
      <div class="project">
        <h3>Eleganto Business</h3>
        <a href="https://eleganto.business" target="_blank">Visit Site</a>
      </div>
      <div class="project">
        <h3>Lakras</h3>
        <a href="https://lakras.co" target="_blank">Visit Site</a>
      </div>
    </div>
  </section>

  <section class="services">
    <h2>Services I Offer</h2>
    <ul>
      <li>✅ Shopify Store Setup & Optimization</li>
      <li>✅ Google Merchant & Analytics Integration</li>
      <li>✅ Facebook / Google Ad Campaigns</li>
      <li>✅ AI-Powered Product & Audience Research</li>
      <li>✅ Dropshipping Automation</li>
      <li>✅ Performance-Based Marketing Strategy</li>
    </ul>
    <a class="cta" href="mailto:your@email.com">Let's Work Together</a>
  </section>

  <footer>
    <p>© 2025 Momentum Team. Built with strategy & style.</p>
  </footer>

</body>
</html>
