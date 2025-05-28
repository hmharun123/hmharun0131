<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Md. Harun Or Rashid</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    .container {
      padding: 30px;
    }
    img.profile {
      border-radius: 50%;
      width: 200px;
      height: 200px;
      object-fit: cover;
      border: 3px solid #444;
    }
    h1 {
      color: #333;
    }
    p {
      font-size: 18px;
      color: #444;
      max-width: 600px;
      margin: 10px auto;
    }
    .buttons {
      margin-top: 25px;
    }
    a.button {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      background-color: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    a.button:hover {
      background-color: #0056b3;
    }
    a.fiverr {
      background-color: #28a745;
    }
    a.fiverr:hover {
      background-color: #218838;
    }
    .certificate-section {
      margin-top: 40px;
    }
    .certificate-section img {
      max-width: 90%;
      border: 2px solid #ccc;
      box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.2);
    }
    .portfolio-section {
      margin-top: 40px;
    }
    .contact-section {
      margin-top: 50px;
    }
    input, textarea {
      width: 80%;
      max-width: 400px;
      padding: 10px;
      margin: 5px auto;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      margin-top: 10px;
    }
    
<style>
  .hero-section {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    text-align: center;
    height: 100vh;
    background: linear-gradient(to right, #f0f2f5, #e2eafc);
    padding: 20px;
  }

  .hero-content h1 {
    font-size: 48px;
    color: #333;
    margin-bottom: 15px;
  }

  .hero-content h2 {
    font-size: 28px;
    color: #444;
  }

  .typing-text {
    color: #007BFF;
    font-weight: bold;
    border-right: 2px solid #007BFF;
    white-space: nowrap;
    overflow: hidden;
  }

  @media screen and (max-width: 768px) {
    .hero-content h1 {
      font-size: 32px;
    }

    .hero-content h2 {
      font-size: 20px;
    }
    <!-- ======= Hero Section ======= -->
<section id="home" class="hero-section">
  <div class="hero-content">
    <h1>Hi, I'm Harun</h1>
    <h2>I am a <span class="typing-text"></span></h2>
  </div>
</section>

<!-- ======= Hero Section CSS ======= -->
</style>

<!-- ======= Typing Text Script ======= -->
<script>
  const text = ["Web Developer", "Designer", "Freelancer"];
  const typingSpan = document.querySelector(".typing-text");
  let i = 0, j = 0, isDeleting = false;

  function type() {
    let current = text[i];
    if (isDeleting) {
      typingSpan.textContent = current.substring(0, j--);
    } else {
      typingSpan.textContent = current.substring(0, j++);
    }

    if (!isDeleting && j === current.length) {
      isDeleting = true;
      setTimeout(type, 1000); // pause after complete
    } else if (isDeleting && j === 0) {
      isDeleting = false;
      i = (i + 1) % text.length;
    }

    setTimeout(type, isDeleting ? 60 : 120);
  }

  document.addEventListener("DOMContentLoaded", type);
</script>
  </style>
</head>
<body>
  <div class="container">

    <!-- Logo Section -->
    <div style="margin-top: 20px;">
      <img src="harun-logo.png" alt="Harun Logo" style="width: 180px; border-radius: 15px;">
    </div>

    <!-- Profile Photo -->
    <img src="harun.jpg" alt="Harun's Photo" class="profile">

    <h1>Md. Harun Or Rashid</h1>
    <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
    <p><strong>Email:</strong> hmharun796@gmail.com</p>
    <p><strong>Education:</strong> SSC, Lemubari Binoda Sundori High School</p>
    <p><strong>Profession:</strong> Freelancer</p>
    <p><strong>Skills:</strong> Data Entry, E-commerce Data Entry, Web Research, Data Research, Web Scraping, Data Scraping, Copy-Paste, and more.</p>

    <div class="buttons">
      <a class="button fiverr" href="https://www.fiverr.com/s/dDlW3G3" target="_blank">Visit My Fiverr Profile</a>
      <a class="button" href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank">Visit My Facebook</a>
      <a class="button" href="https://www.instagram.com/p/DIeAfFXT_oO/" target="_blank">View My Instagram</a>
      <a class="button" href="https://www.tiktok.com/@user6071584366187" target="_blank">TikTok</a>
      <a class="button" href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" target="_blank">WhatsApp</a>
    </div>

    <div class="certificate-section">
      <h2>Certificate of Completion</h2>
      <img src="certificate.jpg" alt="Certificate">
    </div>

    <div class="youtube-section" style="margin-top: 40px;">
      <h2>My YouTube Channel</h2>
      <p>Subscribe to my channel for tutorials, tips, and more!</p>
      <a class="button" href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube</a>
    </div>

    <div class="portfolio-section">
      <h2>My Portfolio</h2>
      <p>Here are some examples of the data entry work I've done:</p>
      <div class="buttons">
        <a class="button" href="https://docs.google.com/spreadsheets/d/1FSV3CzDlRSDJHaumYrCcvKFcBKGedUhFU9qPDY6viW4/edit?usp=drivesdk" target="_blank">
          View Sample Data Entry Work
        </a>
      </div>
    </div>

    <div class="contact-section">
      <h2>Contact Me</h2>
      <form action="https://formspree.io/f/mjvnavrw" method="POST">
        <input type="text" name="name" placeholder="Your Name" required><br><br>
        <input type="email" name="email" placeholder="Your Email" required><br><br>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea><br><br>
        <button type="submit" class="button">Send Message</button>
      </form>
    </div>

  </div>
</body>
</html>
