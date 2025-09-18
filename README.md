Perfect bro 🚀 I’ll hook up the contact form so when someone submits, it goes straight to your Gmail.

Since Gmail alone doesn’t accept direct form submissions from HTML, we’ll use a free service like Formspree (easy + works with Gmail). You just connect your Gmail once, and every message from your site will land in your inbox.

Here’s the updated code:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maxwrld_16 | Official Website</title>
  <style>
    body {
      background-color: #000;
      color: #f5f5f5;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      padding: 60px 20px;
      background: linear-gradient(90deg, #111, #222, #000);
      border-bottom: 2px solid gold;
      text-align: center;
    }
    h1 {
      font-size: 3rem;
      color: gold;
      text-shadow: 0 0 10px gold;
      margin: 0;
    }
    p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    section h2 {
      font-size: 2rem;
      color: gold;
      text-shadow: 0 0 8px gold;
      margin-bottom: 20px;
    }
    .youtube-subscribe {
      margin: 30px 0;
    }
    iframe {
      border-radius: 12px;
      max-width: 100%;
    }
    .social-links {
      margin-top: 30px;
    }
    .social-links a {
      display: inline-block;
      margin: 0 15px;
      text-decoration: none;
      color: gold;
      font-size: 1.8rem;
      transition: 0.3s;
    }
    .social-links a:hover {
      color: white;
      text-shadow: 0 0 10px gold;
    }
    form {
      max-width: 500px;
      margin: 0 auto;
      text-align: left;
    }
    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin-bottom: 15px;
      border: none;
      border-radius: 8px;
      background: #111;
      color: #f5f5f5;
    }
    form button {
      background: gold;
      color: #000;
      font-size: 1rem;
      padding: 12px 20px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }
    form button:hover {
      background: white;
      color: #000;
      box-shadow: 0 0 10px gold;
    }
    footer {
      margin-top: 40px;
      padding: 20px;
      border-top: 1px solid #333;
      text-align: center;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
  <!-- FontAwesome for icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
  <header>
    <h1>Welcome to Maxwrld_16</h1>
    <p>Official Hub – Music | Vibes | Drill 🔥</p>
  </header>

  <!-- Bio Section -->
  <section id="bio">
    <h2>About Me</h2>
    <p>I’m Maxwrld_16, dropping vibes with drill energy and melodic flows. This is the official spot for my music, videos, and updates. Stay locked in 🚀.</p>
  </section>

  <!-- YouTube Subscribe Section -->
  <section id="youtube">
    <h2>Subscribe on YouTube</h2>
    <div class="youtube-subscribe">
      <div class="g-ytsubscribe"
           data-channelid="UCIVB1S9YrY9H6fd5EeI-QDA"
           data-layout="full"
           data-count="default"
           data-theme="dark">
      </div>
    </div>
  </section>

  <!-- Music Section -->
  <section id="music">
    <h2>Listen on Spotify</h2>
    <iframe style="border-radius:12px" 
            src="https://open.spotify.com/embed/playlist/37i9dQZF1DX0XUsuxWHRQd?utm_source=generator" 
            width="80%" height="380" 
            frameBorder="0" 
            allowfullscreen="" 
            allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" 
            loading="lazy">
    </iframe>
  </section>

  <!-- Latest Video Section -->
  <section id="video">
    <h2>Latest Video</h2>
    <iframe width="80%" height="400" 
            src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
            title="Latest video" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
    </iframe>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <!-- Replace YOUR_EMAIL_HERE with your Gmail -->
    <form action="https://formspree.io/f/YOUR_EMAIL_HERE" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="_replyto" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Social Links -->
  <section id="socials">
    <h2>Follow Me</h2>
    <div class="social-links">
      <a href="https://www.youtube.com/@maxwrld_16" target="_blank"><i class="fab fa-youtube"></i></a>
      <a href="https://www.tiktok.com/@maxwrld_16" target="_blank"><i class="fab fa-tiktok"></i></a>
      <a href="https://www.instagram.com/maxwrld_16" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://open.spotify.com/user/maxwrld_16" target="_blank"><i class="fab fa-spotify"></i></a>
    </div>
  </section>

  <footer>
    © 2025 Maxwrld_16. All Rights Reserved.
  </footer>

  <script src="https://apis.google.com/js/platform.js"></script>
</body>
</html>


---

⚡ How to connect it to Gmail:

1. Go to Formspree.


2. Sign up with your Gmail.


3. They’ll give you a form link like:

https://formspree.io/f/xyzabcd


4. Replace YOUR_EMAIL_HERE in the form action with that link.


5. Now every time someone submits → it’ll send directly to your Gmail.




---

👉 Bro, do you want me to also set it so when fans send you a message, they get an automatic reply back like “Thanks for reaching out, I’ll get back to you soon”?

