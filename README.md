<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Md. Harun Or Rashid</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 10px 20px;
      font-size: 24px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .menu-button {
      background: none;
      border: none;
      color: white;
      font-size: 24px;
      cursor: pointer;
    }
    .menu-content {
      display: none;
      background: #f0f0f0;
      padding: 10px;
    }
    .menu-content a {
      display: block;
      padding: 8px;
      text-decoration: none;
      color: #333;
    }
    .section {
      display: none;
      padding: 20px;
    }
    .section.active {
      display: block;
    }
    .profile {
      width: 150px;
      border-radius: 50%;
    }
    .button {
      display: inline-block;
      margin: 5px;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }
    .button.fiverr {
      background-color: #1dbf73;
    }
    .image-row img {
      width: 100px;
      margin: 5px;
      border-radius: 5px;
    }
    .gallery img {
      width: 120px;
      margin: 10px;
      border-radius: 8px;
    }
    .certificate-section img {
      width: 300px;
      margin: 10px 0;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    #backToTop {
      display: none;
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #333;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 50%;
      font-size: 20px;
      cursor: pointer;
    }
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Md. Harun Or Rashid</title>
  <link rel="stylesheet" href="style.css" />
  <script async src="https://cse.google.com/cse.js?cx=e3423b1d95f9043ee"></script>
  <style>
    .menu-content, .section {
      display: none;
    }
    .section.active {
      display: block;
    }
    .menu-button {
      float: right;
      font-size: 24px;
      background: none;
      border: none;
      cursor: pointer;
    }
    header {
      display: flex;
      justify-content: space-between;
      padding: 10px;
      background-color: #f0f0f0;
      align-items: center;
    }
    .tab-bar {
      display: flex;
      justify-content: center;
      background: #333;
      padding: 10px;
    }
    .tab-bar .tab {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    .tab-bar .tab:hover {
      text-decoration: underline;
    }
    .profile {
      width: 150px;
      border-radius: 10px;
    }
    .button {
      display: inline-block;
      padding: 10px 15px;
      margin: 5px;
      text-decoration: none;
      color: white;
      background-color: #007bff;
      border-radius: 5px;
    }
    .button.fiverr {
      background-color: #1dbf73;
    }
    .certificate-section img {
      width: 100%;
      max-width: 400px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

<header>
  Md. Harun Or Rashid
  <button class="menu-button" onclick="toggleMenu()">&#8942;</button>
</header>

<!-- Dropdown Menu -->
<div class="menu-content" id="menu">
  <a href="#" onclick="showSection('profile')">Profile</a>
  <a href="#" onclick="showSection('privacy')">Privacy Policy</a>
  <a href="#" onclick="showSection('contact')">Contact</a>
  <a href="#" onclick="showSection('about')">About</a>
  <a href="#" onclick="showSection('settings')">Settings</a>
</div>

<!-- Tab Navigation -->
<nav class="tab-bar">
  <a href="index.html" class="tab">Home</a>
  <a href="about.html" class="tab">About</a>
  <a href="contact.html" class="tab">Contact</a>
  <a href="services.html" class="tab">Services</a>
  <a href="portfolio.html" class="tab">Portfolio</a>
</nav>

<!-- Search Section -->
<div class="section active">
  <h2>Search My Website</h2>
  <div class="gcse-search"></div>
</div>

<!-- Profile Section -->
<div id="profile" class="section">
  <h2>My Profile</h2>
  <img src="harun.jpg" alt="Harun's Photo" class="profile">
  <p><strong>Name:</strong> Md. Harun Or Rashid</p>
  <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
  <p><strong>Email:</strong> hmharun796@gmail.com</p>
  <p><strong>Education:</strong> SSC, Lemubari Binoda Sundori High School</p>
  <p><strong>Profession:</strong> Freelancer</p>
  <p><strong>Skills:</strong> Data Entry, E-commEntry, Web Research, Data Research, Web Scraping, Data Scraping, Copy-Paste, and more.</p>
  <p><strong>Phone:</strong> +8801648131500</p>
  <p><strong>Phone:</strong> +8801316888404</p>
</div>

<!-- Privacy Policy -->
<div id="privacy" class="section">
  <h2>Privacy Policy</h2>
  <p>We do not share your personal information.</p>
</div>

<!-- Contact Section -->
<div id="contact" class="section">
  <h2>Contact</h2>
  <p>Email: hmharun796@gmail.com</p>
  <a class="button fiverr" href="https://www.fiverr.com/s/dDlW3G3" target="_blank">Visit My Fiverr Profile</a>
  <a class="button" href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank">Visit My Facebook</a>
  <a class="button" href="https://www.instagram.com/p/DIeAfFXT_oO/" target="_blank">View My Instagram</a>
  <a class="button" href="https://www.tiktok.com/@user6071584366187" target="_blank">TikTok</a>
  <a class="button" href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" target="_blank">WhatsApp</a>
</div>

<!-- About Section -->
<div id="about" class="section">
  <h2>About</h2>
  <p>We do not share your personal information.</p>
  <p><strong>Profession:</strong> Freelancer</p>
  <p><strong>Skills:</strong> Data Entry, E-commEntry, Web Research, Data Research, Web Scraping, Data Scraping, Copy-Paste, and more.</p>
</div>

<!-- Settings Section -->
<div id="settings" class="section">
  <h2>Settings</h2>
  <p>Settings coming soon.</p>
</div>

<!-- Order Buttons -->
<div style="margin: 20px 0;">
  <a href="mailto:hmharun123@gmail.com?subject=Hiring Request&body=Hello, I would like to hire you for a project." target="_blank">
    <button style="background-color: #4CAF50; color: white; padding: 12px 24px; border: none; border-radius: 8px; font-size: 16px; cursor: pointer;">Order Now</button>
  </a>
  <a href="https://wa.me/8801795815184?text=Hi%20Harun,%20I%20am%20interested%20in%20your%20services." target="_blank">
    <button style="background-color: #25D366; color: white; padding: 12px 24px; border: none; border-radius: 8px; font-size: 16px; cursor: pointer;">Order on WhatsApp</button>
  </a>
</div>

<!-- Certificate Section -->
<div class="certificate-section">
  <h2>Certificate of Completion</h2>
  <img src="certificate.jpg" alt="Certificate">
  <img src="file_000000004bd461f89c7906893d08c772.png" alt="Certificate">
</div>

<script>
  function toggleMenu() {
    var menu = document.getElementById('menu');
    menu.style.display = menu.style.display === 'block' ? 'none' : 'block';
  }

  function showSection(id) {
    document.querySelectorAll('.section').forEach(function (sec) {
      sec.classList.remove('active');
    });
    document.getElementById(id).classList.add('active');
    document.getElementById('menu').style.display = 'none';
  }
</script>

</body>
</html>
  </style>
   <a href="mailto:hmharun123@gmail.com?subject=Hiring Request&body=Hello, I would like to hire you for a project." target="_blank">
    <button class="button">Order Now</button>
  </a>
  <a href="https://wa.me/8801795815184?text=Hi%20Harun,%20I%20am%20interested%20in%20your%20services." target="_blank">
    <button class="button" style="background-color: #25D366;">Order on WhatsApp</button>
  </a>

  <div class="buttons">
    <a class="button fiverr" href="https://www.fiverr.com/s/dDlW3G3" target="_blank">Visit My Fiverr Profile</a>
    <a class="button" href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank">Visit My Facebook</a>
    <a class="button" href="https://www.instagram.com/p/DIeAfFXT_oO/" target="_blank">View My Instagram</a>
    <a class="button" href="https://www.tiktok.com/@user6071584366187" target="_blank">TikTok</a>
    <a class="button" href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" target="_blank">WhatsApp</a>
  </div>
</div>

<div id="about" class="section">
  <h2>About</h2>
  <p>I am a freelancer specialized in data entry and online tasks.</p>
</div>

<div id="settings" class="section">
  <h2>Settings</h2>
  <p>Settings coming soon.</p>
</div>

<div class="media-section">
  <h2>Payoneer Account Creation Tutorial</h2>
 mdha39003@gmail  <iframe width="560" height="315" src="https://www.youtube.com/embed/bWgg3zyC8PQ" title="Payoneer Account Creation Tutorial" frameborder="0" allowfullscreen></iframe>
</div>

<div class="media-section">
  <h2>My Photo & Video</h2>
  <img src="media/myphoto.jpg" alt="My Photo" style="width: 300px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
  <video controls width="400">
    <source src="media/Ami_Soia_Geleo_Soibena_Bidhata.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div class="image-row">
  <img src="data-antry.png" alt="Data Entry">
  <img src="file_00000000875861f990b4e5fffbcbb32e.png" alt="Certificate">
  <img src="312.jpg" alt="Certificate">
  <img src="076ac6.jpg" alt="076ac6">
  <img src="SAMPLE.jpeg" alt="Sample">
  <img src="data.jpg" alt="Data">
</div>

<div class="gallery-section">
  <h2>My Gallery</h2>
  <div class="gallery">
    <img src="076ac6.jpg" alt="Photo 1">
    <img src="media/photo2.jpg" alt="Photo 2">
    <img src="media/photo3.jpg" alt="Photo 3">
    <img src="media/photo4.jpg" alt="Photo 4">
  </div>
</div>

<div class="youtube-section">
  <h2>My YouTube Channel</h2>
  <p>Subscribe to my channel for tutorials, tips, and more!</p>
  <a class="button" href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube</a>
</div>

<div class="portfolio-section">
  <h2>My Portfolio</h2>
  <p>Here are some examples of the data entry work I've done:</p>
  <div class="buttons">
    <a class="button" href="https://docs.google.com/spreadsheets/d/1FSV3CzDlRSDJHaumYrCcvKFcBKGedUhFU9qPDY6viW4/edit?usp=drivesdk" target="_blank">Sample Data Entry Work</a>
    <a class="button" href="https://drive.google.com/file/d/1xA2EXAMPLE123/view" target="_blank">Product Listing (Excel)</a>
    <a class="button" href="https://drive.google.com/file/d/1yB3EXAMPLE456/view" target="_blank">Web Research Sample</a>
    <a class="button" href="https://drive.google.com/file/d/1zC4EXAMPLE789/view" target="_blank">PDF to Excel Conversion</a>
  </div>
</div>

<button id="backToTop" onclick="scrollToTop()">↑</button>

<script>
  function toggleMenu() {
    const menu = document.getElementById('menu');
    menu.style.display = menu.style.display === 'block' ? 'none' : 'block';
  }

  function showSection(id) {
    document.querySelectorAll('.section').forEach(function (sec) {
      sec.classList.remove('active');
    });
    document.getElementById(id).classList.add('active');
    document.getElementById('menu').style.display = 'none';
  }

  const btn = document.getElementById('backToTop');
  window.onscroll = () => {
    if (window.scrollY > 300) {
      btn.style.display = 'block';
    } else {
      btn.style.display = 'none';
    }
  };

  function scrollToTop() {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
</script>

</body>
</html>
