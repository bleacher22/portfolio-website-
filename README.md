<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sree Sivesh S | Portfolio</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #dcaef4, #6dce7d);
  color: #1f2933;
  line-height: 1.8;
    }

    header {
       background: linear-gradient(135deg, #21e7d6df, #9ab610);
  color: white;
  padding: 75px 20px;
  text-align: center;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 600;
    }

    header p {
      margin: 14px 0;
      font-size: 1.2rem;
    }

    nav {
      margin-top: 20px;
    }

    nav a {
      color: #e6fffa;
      margin: 0 14px;
      text-decoration: none;
      font-weight: 500;
    }

    section {
      padding: 65px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      margin-bottom: 30px;
      color: #134e5e;
      text-align: center;
      font-size: 2.2rem;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 28px;
    }

    .card {
      background: white;
      padding: 28px;
      border-radius: 16px;
      box-shadow: 0 12px 30px rgba(0,0,0,0.08);
      text-align: center;
    }

    footer {
      background: #0f172a;
      color: #cbd5e1;
      text-align: center;
      padding: 30px;
      margin-top: 60px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.3rem;
      }

      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>SREE SIVESH S</h1>
    <p>Computer Science Engineer | Web Developer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#certifications">certifications</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
      
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p style="text-align:center;">
      I am a passionate Computer Science student with a strong interest in web development and a growing curiosity in the data science domain. I am also highly motivated to develop my skills in artificial intelligence, as I believe it plays a crucial role in shaping the future of technology.
    </p>
    <br>
    <p style="text-align:center;">
      I have completed several certifications in Dart & Flutter, Python, and UI/UX design through well-known learning platforms such as Udemy, which have helped me build a solid technical foundation. In addition, I have actively participated in technical events, including Snap AR/VR, where my team secured first place, reflecting my ability to collaborate and innovate effectively.
    </p>
     <br>
    <p style="text-align:center;">
      I am enthusiastic about working in both frontend and backend development. Currently, I am focusing on strengthening my backend development skills to become a well-rounded developer. I am a quick learner who can grasp new concepts efficiently and apply them effectively. I am committed, hardworking, and always strive to give my full potential to every task I take on.
    </p>
  </section>

  <section id="education">
    <h2>Education</h2>
    <p style="text-align:center;">
      <strong>B.E – Computer Science Engineering</strong><br>
      Bannari Amman Institute of Technology<br>
      2024 – 2028
    </p>
  </section>

  <section id="certifications">
    <h2>Certifications & Courses</h2>
    <div class="skills">

      <div class="card">
        <h3>Paper Presentation</h3>
        <p><strong>Pitch Craft</strong></p>
        <p>Presented innovative ideas with structured problem statements and solutions.</p>
      </div>

      <div class="card">
        <h3>Hackathon</h3>
        <p><strong>Snap AR Hackathon</strong></p>
        <p>Developed creative augmented reality experiences using Snap AR tools.</p>
      </div>

      <div class="card">
        <h3>Course Completion</h3>
        <p><strong>Python Programming</strong></p>
        <p>Covered core Python concepts, logic building, and problem solving.</p>
      </div>

      <div class="card">
        <h3>Course Completion</h3>
        <p><strong>Flutter Development</strong></p>
        <p>Learned cross-platform mobile app development using Flutter and Dart.</p>
      </div>

      <div class="card">
        <h3>Course Completion</h3>
        <p><strong>Data Science with Python</strong></p>
        <p>Learned data analysis, visualization, and basic machine learning concepts.</p>
      </div>

    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card">HTML</div>
      <div class="card">CSS</div>
      <div class="card">Python</div>
      <div class="card">C</div>
      <div class="card">Flutter</div>
      <div class="card">Java(Begineer)</div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">

      <div class="card">
        <h3>Biz Guide AI</h3>
        <p>Problem Faced by Rural Entrepreneurs: Starting a business in India is challenging, especially for people in villages or small towns who often struggle with registration and accessing government schemes due to lack of guidance.</p>
      </div>

      <div class="card">
        <h3>Smart Darshan Booking</h3>
        <p>The Smart Darshan Booking App is built with scalability and security in mind, ensuring safe transactions and reliable performance even during peak festival seasons. Overall, it bridges technology and tradition by making temple visits more organized, accessible, and stress-free</p>
      </div>

      <div class="card">
        <h3>Farm Smart</h3>
        <p>Farm Smart is an AI-powered app that helps Indian farmers—especially youth and smallholders—make better farming decisions with real-time, multilingual support.It provides access to crop prices, government schemes, weather alerts, expert advice, and community support, even offline</p>
      </div>

    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center;">Email: sreesiveshs.cs24@bitsathy.ac.in</p>
    <p style="text-align:center;">GitHub: https://github.com/bleacher22</p>
    <p style="text-align:center;">LinkedIn: www.linkedin.com/in/sree-sivesh-s-18a56a352</p>
    <p style="text-align:center;">Phone: 9042609000</p>
  </section>

  <footer>
    <p>© 2025 Sree Sivesh | Built with HTML & CSS</p>
  </footer>

</body>
</html>
