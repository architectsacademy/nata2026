<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Architects Academy - NATA Course 2026</title>
  <link href="https://fonts.googleapis.com/css2?family=Arsenal:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Arsenal', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      overflow-x: hidden;
    }
    header {
      background: linear-gradient(135deg, #bbd2e8 0%, #edb3a5 100%);
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px 50px;
      position: relative;
    }
    header img {
      height: 60px;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      font-weight: 700;
      color: #fff;
      letter-spacing: 0.5px;
    }
    header h2 {
      margin: 0;
      font-size: 1rem;
      font-weight: 400;
      color: rgba(255, 255, 255, 0.9);
    }
    .intro {
      text-align: center;
      padding: 80px 20px;
      max-width: 900px;
      margin: auto;
    }
    .intro h1 {
      font-size: 2.8rem;
      font-weight: 700;
      color: #2c3e50;
    }
    .intro p {
      font-size: 1.15rem;
      color: #555;
      line-height: 1.8;
      font-weight: 400;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 40px;
      padding: 70px 50px;
      background: linear-gradient(135deg, #ffffff, #f8fbfd);
    }
    .feature {
      border-radius: 20px;
      padding: 40px 25px;
      text-align: center;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.05);
      transition: transform 0.4s ease, box-shadow 0.4s ease;
      position: relative;
      color: #2c3e50;
    }
    .feature:nth-child(1) {
      background: #fde2e2;
    }
    .feature:nth-child(2) {
      background: #e2f0cb;
    }
    .feature:nth-child(3) {
      background: #d0e8f2;
    }
    .feature:nth-child(4) {
      background: #fff5ba;
    }
    .feature:nth-child(5) {
      background: #fcd5ce;
    }
    .feature:hover {
      transform: translateY(-8px);
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.1);
    }
    .feature h3 {
      margin-top: 0;
      font-size: 1.4rem;
      font-weight: 700;
    }
    .feature p {
      font-size: 1rem;
      font-weight: 400;
    }
    .cta {
      text-align: center;
      padding: 60px 20px;
      background: #1a233a; /* Dark navy blue */
    }
    .cta a {
      font-family: 'Arsenal', sans-serif;
      display: inline-block;
      padding: 16px 48px;
      font-size: 1.25rem;
      font-weight: 700;
      color: #fff; /* white text */
      border: 5px solid #edb3a5;
      border-radius: 50px;
      text-decoration: none;
      box-shadow:
        0 0 10px rgba(237, 179, 165, 0.5),
        0 0 20px rgba(237, 179, 165, 0.4),
        0 0 30px rgba(204, 204, 255, 0.6),
        0 0 40px rgba(179, 237, 237, 0.5),
        0 0 50px rgba(255, 204, 204, 0.5);
      position: relative;
      z-index: 0;
      transition: color 0.3s ease, box-shadow 0.6s ease, transform 0.3s ease;
    }
    .cta a::before {
      content: "";
      position: absolute;
      top: -8px; bottom: -8px; left: -8px; right: -8px;
      border-radius: 58px;
      background: linear-gradient(
        45deg,
        #ffadad,
        #ffd6a5,
        #fdffb6,
        #caffbf,
        #9bf6ff,
        #a0c4ff,
        #bdb2ff,
        #ffc6ff
      );
      background-size: 400% 400%;
      animation: pastelRainbowGlow 15s linear infinite;
      filter: blur(10px);
      opacity: 1;
      z-index: -1;
    }
    .cta a:hover {
      color: #fff; /* stays white */
      background-color: #edb3a5;
      box-shadow:
        0 0 8px rgba(237, 179, 165, 0.7),
        0 0 15px rgba(237, 179, 165, 0.5),
        0 0 20px rgba(204, 204, 255, 0.7),
        0 0 25px rgba(179, 237, 237, 0.5),
        0 0 30px rgba(255, 204, 204, 0.5);
      transform: scale(1.07);
    }
    @keyframes pastelRainbowGlow {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }
    footer {
      background-color: #2c3e50;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <div>
      <img src="logo.png" alt="Architects Academy Logo" />
    </div>
    <div>
      <h1>Architects Academy</h1>
      <h2>NATA Course 2026</h2>
    </div>
  </header>

  <section class="intro">
    <h1>Design Your Future, One Blueprint at a Time</h1>
    <p>
      Step into the world of architecture with our creative, structured, and inspiring course for
      NATA 2026. Combining professional precision with artistic flair, our program helps you master
      concepts, practice with purpose, and bring your design visions to life.
    </p>
  </section>

  <section class="features">
    <div class="feature">
      <h3>Organized Topic Notes</h3>
      <p>Beautifully formatted, easy-to-digest notes for efficient learning.</p>
    </div>
    <div class="feature">
      <h3>Mock Tests</h3>
      <p>Simulated real-exam environments to boost your confidence.</p>
    </div>
    <div class="feature">
      <h3>Topic Videos</h3>
      <p>Visually engaging lessons designed for deep understanding.</p>
    </div>
    <div class="feature">
      <h3>Flashcards</h3>
      <p>Quick, colorful revision tools to keep key facts fresh in mind.</p>
    </div>
    <div class="feature">
      <h3>Interactive Games</h3>
      <p>Fun challenges to test and sharpen your design skills.</p>
    </div>
  </section>

  <section class="cta">
    <a href="https://rzp.io/rzp/architectsacademy" target="_blank">
      Enroll Now – ₹2,999
    </a>
  </section>

  <footer>
    <p>Contact us: architectsacademy.learn@gmail.com</p>
  </footer>
</body>
</html>
<img width="1080" height="1080" alt="logo" src="https://github.com/user-attachments/assets/556b1a82-42f5-451f-955c-6676591e0c59" />
