# PRODIGY_WD_04
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pratibha Sanj - Web Developer Portfolio</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/js/all.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        header {
            background: #1e3a8a;
            color: #ffffff;
            padding-top: 10px;
            min-height: 10px;
            border-bottom: #3b82f6 3px solid;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            margin: 0;
            list-style: none;
            overflow: hidden;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        header .highlight, header .current a {
            color: #3b82f6;
            font-weight: bold;
        }
        header a:hover {
            color: #ffffff;
            font-weight: bold;
        }
        #showcase {
            min-height: 400px;
            background: url('/api/placeholder/1200/400') no-repeat center center/cover;
            text-align: center;
            color: #ffffff;
        }
        #showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        #showcase p {
            font-size: 20px;
        }
        #skills, #projects, #accomplishments {
            margin-top: 20px;
        }
        .skill-item, .project-item, .accomplishment-item {
            background: #e0f2fe;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
        }
        footer {
            padding: 20px;
            margin-top: 20px;
            color: #ffffff;
            background-color: #1e3a8a;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">Pratibha Sanj</span> Web Developer</h1>
            </div>
            <nav>
                <ul>
                    <li class="current"><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#accomplishments">Accomplishments</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="showcase">
        <div class="container">
            <h1>Professional Web Developer</h1>
            <p>Turning ideas into interactive realities</p>
        </div>
    </section>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I'm Pratibha Sanj, a passionate web developer with a keen interest in creating responsive and user-friendly websites. I graduated from Jain University with a degree in Master of Computer Applications, which has provided me with a strong foundation in computer science and software development.</p>
            <p>My journey in web development began during my studies, and I've since been continuously learning and applying new technologies to solve real-world problems. I'm excited to bring my skills and enthusiasm to challenging projects and contribute to the ever-evolving world of web development.</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skill-item">
                <h3>Front-end Development</h3>
                <p>HTML5, CSS3, JavaScript, React, Vue.js</p>
            </div>
            <div class="skill-item">
                <h3>Back-end Development</h3>
                <p>Node.js, Python, PHP, SQL, MongoDB</p>
            </div>
            <div class="skill-item">
                <h3>Other Technologies</h3>
                <p>Git, Docker, AWS, Agile Methodologies</p>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project-item">
                <h3>E-commerce Platform</h3>
                <p>Developed a fully functional e-commerce website using React for the front-end and Node.js for the back-end. Implemented features such as user authentication, product catalog, shopping cart, and payment integration.</p>
            </div>
            <div class="project-item">
                <h3>Task Management App</h3>
                <p>Created a responsive task management application using Vue.js and Firebase. Features include real-time updates, user collaboration, and data visualization for productivity tracking.</p>
            </div>
            <div class="project-item">
                <h3>Portfolio Website Generator</h3>
                <p>Built a tool that allows users to create their own portfolio websites by inputting their information. The generator creates a custom website using HTML, CSS, and JavaScript, which users can download and deploy.</p>
            </div>
        </section>

        <section id="accomplishments">
            <h2>Accomplishments</h2>
            <div class="accomplishment-item">
                <h3>Academic Excellence</h3>
                <p>Graduated with distinction from the Master of Computer Applications program at Jain University.</p>
            </div>
            <div class="accomplishment-item">
                <h3>Hackathon Participant</h3>
                <p>Participated in the 2023 Code for Good Hackathon, developing innovative solutions for non-profit organizations.</p>
            </div>
            <div class="accomplishment-item">
                <h3>Web Development Certification</h3>
                <p>Completed a comprehensive Full Stack Web Development certification, enhancing skills in modern web technologies.</p>
            </div>
        </section>
    </div>

    <footer>
        <p>Pratibha Sanj Web Developer, Copyright &copy; 2024</p>
        <div>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-github"></i></a>
        </div>
    </footer>
</body>
</html>
