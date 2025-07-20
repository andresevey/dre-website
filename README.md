# dre-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Andres Evey | Personal Website</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #0077b6;
      --accent: #90e0ef;
      --bg: #f7f9fa;
      --text: #1e1e1e;
    }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background: var(--primary);
      color: white;
      padding: 4rem 2rem;
      text-align: center;
    }

    header h1 {
      margin-bottom: 0.5rem;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }

    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin: 2rem auto;
      display: block;
      border: 4px solid white;
    }

    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    h2 {
      color: var(--primary);
      border-bottom: 2px solid var(--accent);
      display: inline-block;
      margin-bottom: 1rem;
    }

    .contact {
      text-align: center;
      margin: 3rem 0;
    }

    .contact a {
      color: var(--primary);
      font-weight: 600;
      text-decoration: none;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #777;
    }

    .social-links a {
      margin: 0 0.5rem;
      color: var(--primary);
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <img src="your-photo.jpg" alt="Andres Evey" class="profile-pic" />
    <h1>Andres Evey</h1>
    <p>Friends call me Dre. Sustainability Strategist | Ocean Enthusiast | Positive Human</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>
      I'm a sustainability consultant focused on building strategies that protect the planet and drive business forward. With a background in finance and a passion for the ocean, I bring both analytical rigor and heart to my work. Outside of work, you'll find me surfing, camping, or chasing my kids around a sunny beach.
    </p>
  </section>

  <section>
    <h2>Experience</h2>
    <p>
      Currently at Deloitte, I work in the Sustainability Strategy practice serving tourism, hospitality, and service clients. My career started in risk management, where I focused on reducing exposure from third-party business relationships.
    </p>
    <p>
      My goal? Drive $10M in sustainability strategy revenue by 2026 — and make the world a little better while doing it.
    </p>
  </section>

  <section>
    <h2>Skills & Interests</h2>
    <ul>
      <li>Corporate Sustainability & ESG Strategy</li>
      <li>Ocean Conservation & Marine Biology (in training)</li>
      <li>Leadership, Coaching, and Team Culture</li>
      <li>SCUBA Certified | Surf Addict | Nature Lover</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Contact Me</h2>
    <p>
      Reach out via <a href="mailto:your.email@example.com">email</a> or connect with me on:
    </p>
    <div class="social-links">
      <a href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
      <a href="https://github.com/yourprofile" target="_blank">GitHub</a>
    </div>
    <p><a href="your-resume.pdf" download>Download My Resume</a></p>
  </section>

  <footer>
    © 2025 Andres Evey. Built with heart and HTML.
  </footer>

</body>
</html>
