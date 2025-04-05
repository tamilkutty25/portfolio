# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #ff9a9e, #fad0c4, #fad0c4, #ffdde1);
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #ff7eb3, #ff758c, #ff7eb3);
            color: white;
            text-align: center;
            padding: 3rem 0;
            position: relative;
            border-bottom: 5px solid #ff4d6d;
        }

        .header-content h1 {
            font-size: 2.8rem;
            margin: 0;
        }

        .profile-picture {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            object-fit: cover;
            position: absolute;
            top: 20px;
            left: 20px;
            border: 5px solid white;
        }

        nav {
            background: #ff4d6d;
            text-align: center;
            padding: 1rem 0;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ffdde1;
        }

        .section-content {
            background: white;
            padding: 2rem;
            margin: 2rem auto;
            max-width: 800px;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.15);
            text-align: center;
        }

        .download-button {
            background: #ff4d6d;
            color: white;
            padding: 0.8rem 1.8rem;
            text-decoration: none;
            border-radius: 25px;
            display: inline-block;
            margin-top: 15px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .download-button:hover {
            background: #ff758c;
        }

        footer {
            text-align: center;
            padding: 1.5rem 0;
            background: #222;
            color: white;
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://assets.onecompiler.app/43dtggy8b/43dthcj4e/1000155371.jpg" alt="Profile Picture" class="profile-picture">
        <div class="header-content">
            <h1>TAMILARASI M</h1>
            <p>Web Developer</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
        </ul>
    </nav>

    <section id="about" class="section-content">
        <h2>About Me</h2>
        <p>I am a passionate web developer with expertise in creating dynamic and responsive websites. With 7+ years in the field, I focus on performance, usability, and scalability.</p>
    </section>

    <section id="education" class="section-content">
        <h2>Education</h2>
        <p>Bharathiar University - Kaamadhenu Arts and Science College - B.Sc Computer Science</p>
    </section>

    <section id="skills" class="section-content">
        <h2>Skills</h2>
        <ul>
            <li>React.js</li>
            <li>MERN Stack</li>
            <li>Cloud Computing</li>
            <li>Python & AI/ML</li>
            <li>Spring Boot</li>
            <li>Java & C++</li>
            <li>JavaScript</li>
        </ul>
    </section>

    <section id="projects" class="section-content">
        <h2>Projects</h2>
        <ul>
            <li><a href="#">E-Commerce Platform</a></li>
            <li><a href="#">Cloud Security Project</a></li>
            <li><a href="#">AI Chatbot</a></li>
            <li><a href="#">College Portal</a></li>
        </ul>
    </section>

    <section id="resume" class="section-content">
        <h2>Resume</h2>
        <a href="resume.pdf" target="_blank" class="download-button">Download CV</a>
    </section>

    <footer>
        <p>&copy; 2025 Jaibharathi P</p>
    </footer>
</body>
</html>
