
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HM Harun | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }/* Preloader */
#preloader {
  position: fixed;
  width: 100%;
  height: 100%;
  background: #fff;
  z-index: 9999;
  display: flex;
  align-items: center;
  justify-content: center;
}
.loader {
  border: 6px solid #f3f3f3;
  border-top: 6px solid #3498db;
  border-radius: 50%;
  width: 50px;
  height: 50px;
  animation: spin 1s linear infinite;
}
@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
/* Navbar */
.navbar {
  position: sticky;
  top: 0;
  background: #333;
  padding: 1rem;
  color: #fff;
  z-index: 1000;
}
.navbar .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.nav-links {
  list-style: none;
  display: flex;
}
.nav-links li {
  margin-left: 20px;
}
.nav-links a {
  color: #fff;
  text-decoration: none;
}
/* Hero */
#hero {
  height: 100vh;
  background: #f5f5f5;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.typed-text {
  font-weight: bold;
  color: #3498db;
}
.cursor {
  display: inline-block;
  animation: blink 0.7s infinite;
}
@keyframes blink {
  0%, 100% { opacity: 1; }
  50% { opacity: 0; }
}
.btn {
  padding: 10px 20px;
  background: #3498db;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 20px;
}
/* Sections */
section {
  padding: 60px 20px;
  text-align: center;
}
/* Testimonials */
#testimonials {
  background: #f0f0f0;
}
.testimonial-container {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.testimonial {
  background: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}
.testimonial h4 {
  margin-top: 10px;
  font-style: italic;
  color: #555;
}
/* Scroll Animations */
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  transition: opacity 0.8s ease, transform 0.8s ease;
}
.fade-in.show {
  opacity: 1;
  transform: translateY(0);
}
/* Footer */
footer {
  background: #333;
  color: #fff;
  padding: 20px 10px;
  text-align: center;
}
footer .social-links a {
  margin: 0 10px;
  color: #fff;
  text-decoration: none;
}
/* Back to Top */
#backToTop {
  position: fixed;
  bottom: 20px;
  right: 20px;
  display: none;
  background: #3498db;
  color: white;
  border: none;
  padding: 10px 15px;
  font-size: 20px;
  border-radius: 50%;
  cursor: pointer;
  z-index: 999;
}
/* Responsive */
@media (max-width: 768px) {
  .navbar .container {
    flex-direction: column;
    align-items: flex-start;
  }
  .nav-links {
    flex-direction: column;
    gap: 10px;
    margin-top: 10px;
  }
  .testimonial-container {
    flex-direction: column;
  }
  .btn {
    width: 100%;
    text-align: center;
  }
}

  </style>
</head>
<body>
  <div id="preloader">
    <div class="loader"></div>
  </div>  <nav class="navbar">
    <div class="container">
      <h1 class="logo">HM Harun</h1>
      <ul class="nav-links">
        <li><a href="#hero">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>  <section id="hero" class="fade-in">
    <div class="hero-content">
      <h1>Hi, I'm Harun</h1>
      <h2><span class="typed-text"></span><span class="cursor">|</span></h2>
      <a href="cv.pdf" class="btn" download>Download CV</a>
    </div>
  </section>  <section id="about" class="fade-in">
    <h2>About Me</h2>
    <p>Your short bio goes here.</p>
  </section>  <section id="projects" class="fade-in">
    <h2>My Projects</h2>
    <p>Project samples go here.</p>
  </section>  <section id="testimonials" class="fade-in">
    <h2>Testimonials</h2>
    <div class="testimonial-container">
      <div class="testimonial">
        <p>"Harun is very talented and delivers high quality work!"</p>
        <h4>- Client A</h4>
      </div>
      <div class="testimonial">
        <p>"A great developer to work with. Highly recommended!"</p>
        <h4>- Client B</h4>
      </div>
    </div>
  </section>  <section id="contact" class="fade-in">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>  <footer>
    <p>© 2025 HM Harun. All rights reserved.</p>
    <div class="social-links">
      <a href="#">Facebook</a>
      <a href="#">LinkedIn</a>
      <a href="#">GitHub</a>
    </div>
  </footer><button id="backToTop" title="Back to Top">↑</button>

  <script>
    window.addEventListener("load", function () {
      document.getElementById("preloader").style.display = "none";
    });

    const texts = ["a Web Developer", "a Freelancer", "a Designer"];
    let count = 0;
    let index = 0;
    let currentText = "";
    let letter = "";

    (function type() {
      if (count === texts.length) count = 0;
      currentText = texts[count];
      letter = currentText.slice(0, ++index);

      document.querySelector(".typed-text").textContent = letter;
      if (letter.length === currentText.length) {
        count++;
        index = 0;
        setTimeout(type, 1000);
      } else {
        setTimeout(type, 100);
      }
    })();

    const faders = document.querySelectorAll('.fade-in');
    const appearOptions = {
      threshold: 0.3,
      rootMargin: "0px 0px -50px 0px"
    };
    const appearOnScroll = new IntersectionObserver(function(entries, observer) {
      entries.forEach(entry => {
        if (!entry.isIntersecting) return;
        entry.target.classList.add("show");
        observer.unobserve(entry.target);
      });
    }, appearOptions);
    faders.forEach(fader => {
      appearOnScroll.observe(fader);
    });

    const topButton = document.getElementById("backToTop");
    window.onscroll = function () {
      topButton.style.display = window.scrollY > 200 ? "block" : "none";
    };
    topButton.onclick = () => window.scrollTo({ top: 0, behavior: 'smooth' });
  </script></body>
</html>
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
    </style>
</head>
    <body>
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
