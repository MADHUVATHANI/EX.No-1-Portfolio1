# Ex01 Portfolio
## Date:29-08-2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MADHUVATHANI V| Portfolio</title>
  <link rel="stylesheet" href="portfolio.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
  <header>
    <div class="navbar">
    <div class="nav-left">MADHUVATHANI</div>
    <div class="nav-center">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#certificates">Certificates</a>
      <a href="#contact">Contact-Me</a>
    </div>
    <div class="nav-right">
      <button class="toggle-theme">☀️</button>
    </div>
    </div>
  </header>

  <section class="hero">
   <div class="hero-container" style="display: flex; align-items: center; gap: 20px;">
    
    <!-- Profile Picture -->
    <div class="hero-image" style="flex-shrink: 0;">
      <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\8AFB5804F92F8D5F149BFC66D149AA92\WhatsApp Image 2025-08-29 at 19.20.02_ae7cb058.jpg" alt="MADHUVATHANI v" 
           style="width: 200px; height: 200px; object-fit: cover; border-radius: 50%; border: 3px solid #6c63ff;">
    </div>  
    <div class="hero-text">
      <h2>Hi, I'm <span>MADHUVATHANI V</span></h2>
      <p class="subtitle">B.E CSE</p>
      <p>Software Engineer | Cloud Computing</p>
      <p class="description">
        A third-year undergraduate engineering student at Saveetha Engineering College, Chennai, passionate about Information Technology, AI, and smart systems.
      </p>
      <a href="#contact" class="btn">Contact me <i class="fas fa-arrow-right"></i></a>
    </div>
  </section>

  <section class="section" id="about">
    <h2>About Me</h2>
    <p>      I am a passionate and dedicated undergraduate student pursuing a B.E CSE at Saveetha Engineering College, Chennai, with a CGPA of 8.9(2023–2027). With a keen interest in integrating smart technology into real-world applications,  machine learning, and cloud computing. <br><br>
             I have hands-on experience in building projects like smart irrigation, face detection, fraud detection using ML, and AI-based applications. My goal is to contribute to innovative tech-driven solutions that positively impact society. 
             I’m also an active participant in hackathons and technical events, always eager to learn and grow.I love building smart systems and solving real-world problems using tech.
    </p>
  </section>

  <section class="section" id="education">
    <h2>Academic Background</h2>
    <p><strong>Saveetha Engineering College, Chennai</strong></p>
    <p>B.E CSE, 2023–2027 | GPA: 8.9</p>
  </section>

  <!-- Skills Section -->
  <section class="section" id="skills">
  <h2>Skills</h2>
  <ul class="item-list">
    <li><strong>Programming Languages:</strong> Python, C, HTML, Java</li>
    <li><strong>Cloud Platforms:</strong> AWS, Google Cloud, Things-Speak</li>
    <li><strong>Databases:</strong> MongoDB, SQL</li>
    <li><strong>Tools & Technologies:</strong> Git</li>
    <li><strong>Soft Skills:</strong> Problem-solving, Communication, Time Management, Teamwork</li>
  </ul>
  </section>
  </div>
  </section>



  <section class="section" id="certifications">
  <h2>Certifications</h2>
  <ul class="cert-list">
    <li>Introduction to cloud computing</li>
    <li>Supervised Machine Learning:Regression</li>
    <li>Micro-Certification(ServiceNow)</li>
    <li>Automation Explorer with UiPath Studio Web</li>
    <li>IBM Introduction to Machine Learning</li>
    <li>AI Artificial Intelligence with Python</li>
    <li>Introduction to Industry 4.0 and Industrial Internet Of Things</li>
    <li>Project Management 101</li>

  </ul>
  </section>
  <!-- Contact Section -->
  <section class="section" id="contact">
  <h2>Contact Me</h2>
  <div class="contact-container">
    <form class="contact-form" action="mailto:your-email@example.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <div class="contact-info">
      <p><strong>Email:</strong> madhuvathani733@gmail.com</p>
      <p><strong>Phone:</strong> +91 8124431638 </p>
      <p><strong>Location:</strong> Chennai, India</p>
    </div>
  </div>
  </section>


  <section class="section" id="cv">
    <h2>Download CV</h2>
    <a href="resume.pdf" download class="btn">Download PDF</a>
  </section>

  <footer>
    <p>&copy; 2025 MADHUVATHANI V. All rights reserved.</p>
  </footer>
<style>
    /* Reset & base styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  background-color: #0a0a12;
  color: #f4f4f4;
  line-height: 1.6;
}

header {
  background-color: #0f0f1a;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/* Entire navbar */
.nav-left {
  font-size: 20px;
  font-weight: bold;
  color: #00ffd0;
  margin-right: 30px; /* ✅ This adds space between name and links */
  white-space: nowrap;
}

.navbar {
  display: flex;
  align-items: center;
  background-color: #0f0f20;
  padding: 15px 40px;
}

.nav-center {
  display: flex;
  gap: 25px; /* ✅ Proper spacing between nav items */
  flex-wrap: wrap;
}

.nav-center a {
  text-decoration: none;
  color: white;
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav-center a:hover {
  color: #7c3aed;
}

.nav-right {
  margin-left: auto;
}

.toggle-theme {
  background: none;
  border: none;
  font-size: 22px;
  cursor: pointer;
  color: white;
}


/* Logo (name) styling */
.logo {
  font-size: 24px;
  font-weight: bold;
  color: #00ffd0;
  margin-right: 40px;
}

/* Navigation links styling */
.nav-links {
  display: flex;
  gap: 20px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: #00ffd0;
}

nav h1 {
  font-size: 1.5rem;
  color: #ffffff;
}

nav ul {
  display: flex;
  list-style: none;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #ccc;
  font-weight: 500;
}

nav ul li a:hover {
  color: #8c52ff;
}

.hero {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
  padding: 80px 40px;
}

.hero-text {
  max-width: 500px;
}

.hero-text h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero-text span {
  color: #8c52ff;
}

.subtitle {
  font-size: 1.2rem;
  color: #bbbbbb;
  margin-bottom: 10px;
}

.description {
  margin-bottom: 20px;
}

.btn {
  padding: 10px 20px;
  background: #8c52ff;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  transition: 0.3s;
}

.btn:hover {
  background: #a47dff;
}

.hero-img img {
  width: 280px;
  height: 280px;
  object-fit: cover;
  border-radius: 50% 50% 0 0;
  border: 4px solid #8c52ff;
  box-shadow: 0 0 20px #8c52ff66;
}

.scroll-down {
  text-align: center;
  font-size: 1rem;
  margin-top: 20px;
  color: #8c52ff;
}

#certificates ul {
  list-style-position: inside; /* Ensures bullet points start inside the padding */
  padding-left: 20px;           /* Controls left indentation */
  margin: 0;                   /* Removes default margin */
}

#certificates li {
  margin-left: 0;              /* Removes extra left margin on list items */
  padding-left: 0;             /* Removes padding if any */
}

.content-section {
  text-align: center; /* ⬅️ Center all text */
  max-width: 900px;   /* Optional: to keep things readable */
  margin: 0 auto;     /* ⬅️ Center the entire block horizontally */
  padding: 50px 20px; /* Adds spacing */
}

.content-section h2 {
  font-size: 32px;
  color: #00ffd0;
  margin-bottom: 20px;
}

.content-section h3 {
  font-weight: bold;
  color: white;
}

.content-section p, 
.content-section li {
  font-size: 18px;
  color: #ffffff;
  line-height: 1.7;
}

.content-section ul {
  list-style-type: none;
  padding-left: 0;
}

header h1 {
  font-size: 2.5rem;
  color: #00ffe0;
}

header p {
  font-size: 1.2rem;
  color: #bbbbbb;
}
.section {
  text-align: center;
  margin: 50px 0;
}

.section h2 {
  color: #00ffd0;
  font-size: 32px;
  margin-bottom: 20px;
}

.cert-list {
  list-style: none;
  padding: 0;
  margin: 0 auto;
  max-width: 500px;
  text-align: left;
  font-size: 18px;
  color: #fff;
}

.cert-list li {
  margin-bottom: 15px;
  padding-left: 20px; /* optional, adds space before each item */
  position: relative;
}

.cert-list li::before {
  content: "•";
  position: absolute;
  left: 0;
  color: #00ffd0;
}

.section {
  text-align: center;
  margin: 50px 0;
}

.section h2 {
  color: #00ffd0;
  font-size: 32px;
  margin-bottom: 20px;
}

.item-list {
  list-style: none;
  padding: 0;
  margin: 0 auto;
  max-width: 700px;
  text-align: left;
  font-size: 18px;
  color: #fff;
}

.item-list li {
  margin-bottom: 15px;
  padding-left: 20px;
  position: relative;
}

.item-list li::before {
  content: "•";
  position: absolute;
  left: 0;
  color: #00ffd0;
}

.project-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin-top: 20px;
}

.project-card {
  background-color: #1a1a1a;
  color: #ffffff;
  width: 300px;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0, 255, 208, 0.2);
  transition: transform 0.3s ease;
}

.project-card:hover {
  transform: scale(1.03);
}

.project-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.project-card h3 {
  margin: 15px;
  font-size: 20px;
  color: #00ffd0;
}

.project-card p {
  margin: 0 15px 15px;
  font-size: 15px;
}

.details-button {
  background-color: #00ffd0;
  color: #000;
  border: none;
  padding: 10px 15px;
  margin: 10px 15px;
  border-radius: 8px;
  cursor: pointer;
}

.project-details {
  display: none;
  padding: 0 15px 15px;
  font-size: 14px;
  color: #ccc;
}

.section {
  text-align: center;
  max-width: 900px;
  margin: 0 auto;
  padding: 60px 20px;
  color: #fff;
}

.section h2 {
  font-size: 32px;
  color: #00ffd0;
  margin-bottom: 20px;
}

.section ul {
  list-style: none;
  padding-left: 0;
}

.section li {
  font-size: 18px;
  line-height: 1.6;
}

.section p {
  font-size: 18px;
  line-height: 1.7;
  margin: 10px 0;
}

ul {
  list-style: none;
  padding-left: 20px;
}

ul li::before {
  content: "•";
  color: #00ffe0;
  margin-right: 8px;
}

#contact {
  padding: 50px 20px;
  text-align: center;
}

.contact-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 30px;
  margin-top: 20px;
}

.contact-form {
  width: 100%;
  max-width: 500px;
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #00ffd0;
  border-radius: 8px;
  background-color: #1a1a1a;
  color: #ffffff;
  font-size: 16px;
}

.contact-form button {
  background-color: #00ffd0;
  color: #000;
  padding: 12px;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  font-weight: bold;
  transition: background-color 0.3s ease;
}

.contact-form button:hover {
  background-color: #00c0a3;
}

.contact-info {
  color: #ccc;
  font-size: 16px;
  line-height: 1.6;
}

a.btn {
  display: inline-block;
  background-color: #00ffe0;
  color: #121212;
  padding: 10px 20px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

a.btn:hover {
  background-color: #00c9aa;
}

footer {
  text-align: center;
  margin-top: 40px;
  font-size: 0.9rem;
  color: #888;
}
</style>
</body>
</html>

```
## OUTPUT
<img width="1914" height="1079" alt="image" src="https://github.com/user-attachments/assets/40eb8aab-3069-469e-acab-c4a7a3e2717a" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/47e72b67-5862-4ec8-8ea1-e589088dc879" />
<img width="1913" height="1072" alt="image" src="https://github.com/user-attachments/assets/e2a6bf4f-dc66-4a5d-bb06-2852180cf11b" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
