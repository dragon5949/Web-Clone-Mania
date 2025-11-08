# Web-Clone-Mania<!doctype html> 
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>HackODisha — Hackathon</title>
  <link rel="stylesheet" href="css/styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container">
      <h1 class="logo">HackODisha</h1>
      <nav>
        <a href="#about">About</a>
        <a href="#schedule">Schedule</a>
        <a href="#speakers">Speakers</a>
        <a href="#register">Register</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container">
        <h2>Build. Ship. Impact.</h2>
        <p>Join HackODisha — a 48‑hour hackathon for students and professionals.</p>
        <a class="btn" href="#register">Register Now</a>
      </div>
    </section>

    <section id="about" class="container section">
      <h3>About</h3>
      <p>Collaborate, learn and build projects that solve real problems for Odisha and beyond.</p>
    </section>

    <section id="schedule" class="container section">
      <h3>Schedule</h3>
      <ul class="schedule">
        <li><strong>Day 1</strong> — Kickoff, team formation, workshops</li>
        <li><strong>Day 2</strong> — Hacking continues, mentor sessions</li>
        <li><strong>Day 3</strong> — Final demos & prizes</li>
      </ul>
    </section>

    <section id="speakers" class="container section">
      <h3>Speakers & Mentors</h3>
      <div class="grid">
        <div class="card"><img src="https://via.placeholder.com/120" alt=""><p>Mentor A</p></div>
        <div class="card"><img src="https://via.placeholder.com/120" alt=""><p>Mentor B</p></div>
        <div class="card"><img src="https://via.placeholder.com/120" alt=""><p>Mentor C</p></div>
      </div>
    </section>

    <section id="register" class="container section">
      <h3>Register</h3>
      <form id="registerForm" class="form">
        <label>
          Full name
          <input name="name" type="text" required />
        </label>
        <label>
          Email
          <input name="email" type="email" required />
        </label>
        <label>
          Team name (optional)
          <input name="team" type="text" />
        </label>
        <button type="submit" class="btn">Submit</button>
      </form>
      <div id="msg" aria-live="polite"></div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; <span id="year"></span> HackODisha — All rights reserved.</p>
    </div>
  </footer>

  <script src="js/main.js"></script>
</body>
</html>