### Hi there 👋

<!--
**govindudusrihari/govindudusrihari** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <h1>Welcome to My Portfolio</h1>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am a web developer with a passion for creating beautiful and functional websites. Here, you can find some of the projects I’ve worked on and get in touch with me.</p>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of project 1.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of project 2.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sriharigovindudu's Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #444;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      text-align: center;
    }
    nav a:hover {
      background-color: #555;
    }
    section {
      padding: 20px;
      margin: 20px;
      background-color: white;
      border-radius: 10px;
      display: none;
    }
    .certificates, .awards, .marks {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    .item {
      width: 45%;
      margin: 10px;
      text-align: center;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
    }
    video {
      max-width: 100%;
      border-radius: 10px;
    }
    .active {
      display: block;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sriharigovindudu's Portfolio</h1>
  </header>

  <nav>
    <a href="#" onclick="showSection('intro')">Introduction</a>
    <a href="#" onclick="showSection('certifications')">Certifications</a>
    <a href="#" onclick="showSection('awards')">Awards</a>
    <a href="#" onclick="showSection('marks')">Marks</a>
  </nav>

  <section id="intro" class="active">
    <h2>Self Introduction</h2>
    <video controls>
      <source src="VID_132260610_124105_375.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </section>

  <section id="certifications">
    <h2>Certifications</h2>
    <div class="certificates">
      <div class="item">
        <img src="cert1.jpg" alt="Certification 1">
        <p>Certification Name 1</p>
      </div>
      <div class="item">
        <img src="cert2.jpg" alt="Certification 2">
        <p>Certification Name 2</p>
      </div>
    </div>
  </section>

  <section id="awards">
    <h2>Awards</h2>
    <div class="awards">
      <div class="item">
        <img src="award1.jpg" alt="Award 1">
        <p>Award Name 1</p>
      </div>
      <div class="item">
        <img src="award2.jpg" alt="Award 2">
        <p>Award Name 2</p>
      </div>
    </div>
  </section>

  <section id="marks">
    <h2>Academic Marks</h2>
    <div class="marks">
      <div class="item">
        <img src="10th-mark-card.jpg" alt="10th Mark Card">
        <p>10th Grade Marks</p>
      </div>
      <div class="item">
        <img src="12th-mark-card.jpg" alt="12th Mark Card">
        <p>12th Grade Marks</p>
      </div>
      <div class="item">
        <img src="bachelor-mark-card.jpg" alt="Bachelor's Mark Card">
        <p>Bachelor's Degree Marks</p>
      </div>
    </div>
  </section>

  <script>
    function showSection(sectionId) {
      const sections = document.querySelectorAll('section');
      sections.forEach(section => {
        section.classList.remove('active');
      });
      document.getElementById(sectionId).classList.add('active');
    }
  </script>

</body>
</html>
