<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Xavier Boroski | Portfolio</title>

    <style>
        * {
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            color: #333333;
            background-color: #f4f6f8;
        }

        nav {
            background-color: #1b365d;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 8px 15px;
            font-weight: bold;
            display: inline-block;
        }

        nav a:hover {
            color: #ffb81c;
        }

        header {
            background-color: #1b365d;
            color: white;
            text-align: center;
            padding: 70px 20px;
        }

        header h1 {
            margin: 0;
            font-size: 42px;
        }

        header h2 {
            margin: 10px 0 5px;
            color: #ffb81c;
        }

        header p {
            margin: 0;
            font-size: 18px;
        }

        main {
            width: 90%;
            max-width: 1000px;
            margin: auto;
        }

        section {
            background-color: white;
            margin: 30px 0;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
        }

        section h2 {
            color: #1b365d;
            border-bottom: 3px solid #ffb81c;
            padding-bottom: 8px;
        }

        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            padding: 0;
            list-style: none;
        }

        .skills-list li {
            background-color: #e8eef6;
            color: #1b365d;
            padding: 8px 14px;
            border-radius: 20px;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .project-card {
            background-color: #f4f6f8;
            padding: 20px;
            border-left: 5px solid #ffb81c;
            border-radius: 6px;
        }

        .project-card h3 {
            color: #1b365d;
            margin-top: 0;
        }

        .contact-link {
            color: #1b365d;
            font-weight: bold;
        }

        footer {
            background-color: #1b365d;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        @media (max-width: 700px) {
            header {
                padding: 45px 15px;
            }

            header h1 {
                font-size: 32px;
            }

            nav a {
                display: block;
                margin: 10px;
            }

            .project-grid {
                grid-template-columns: 1fr;
            }

            section {
                padding: 20px;
            }
        }
    </style>
</head>

<body>

    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>

    <header>
        <h1>Xavier Boroski</h1>
        <h2>Marketing Student</h2>
        <p>University of Utah</p>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>
                I am a marketing major at the University of Utah with an emphasis
                in sales. My career goal is to become a marketing director, where
                I can lead teams, develop creative campaigns, build strong customer
                relationships, and help businesses grow. I am especially interested
                in how artificial intelligence can improve marketing through
                automation, personalized advertising, customer analysis, and better
                decision-making. My technical interests include data analytics,
                Excel, information systems, website development, and digital tools
                that support marketing and sales.
            </p>
        </section>

        <section id="skills">
            <h2>Skills</h2>

            <ul class="skills-list">
                <li>Sales and Marketing</li>
                <li>Market Analysis</li>
                <li>Customer Relationship Management</li>
                <li>Hiring and Interviewing</li>
                <li>Leadership</li>
                <li>Team Training</li>
                <li>Sales Coaching</li>
                <li>Communication</li>
                <li>Customer Service</li>
                <li>Conflict Resolution</li>
                <li>Adaptability</li>
                <li>Microsoft Excel</li>
                <li>ChatGPT</li>
                <li>Google Gemini</li>
                <li>Canva</li>
                <li>CapCut</li>
                <li>Adobe Premiere Pro</li>
            </ul>
        </section>

        <section id="projects">
            <h2>Projects</h2>

            <div class="project-grid">
                <div class="project-card">
                    <h3>Marketing Campaign Analysis</h3>
                    <p>
                        Used Excel and ChatGPT to analyze campaign data and
                        compare brand performance.
                    </p>
                </div>

                <div class="project-card">
                    <h3>Sales Training and Leadership</h3>
                    <p>
                        Trained and coached client representatives on sales skills,
                        team goals, and customer relationships.
                    </p>
                </div>

                <div class="project-card">
                    <h3>Video Production and Editing</h3>
                    <p>
                        Created and edited video projects using Adobe Premiere Pro
                        and CapCut.
                    </p>
                </div>

                <div class="project-card">
                    <h3>GitHub Portfolio Website</h3>
                    <p>
                        Built and published a professional portfolio website using
                        HTML, CSS, and GitHub Pages.
                    </p>
                </div>
            </div>
        </section>

        <section id="resume">
            <h2>Resume</h2>
            <p>Updated resume coming soon.</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>

            <p>
                Email:
                <a class="contact-link" href="mailto:u1449141@utah.edu">
                    u1449141@utah.edu
                </a>
            </p>

            <p>
                LinkedIn:
                <a class="contact-link"
                   href="https://www.linkedin.com/in/xavier-boroski/"
                   target="_blank">
                    Xavier Boroski
                </a>
            </p>

            <p>
                GitHub:
                <a class="contact-link"
                   href="https://github.com/YOUR-USERNAME"
                   target="_blank">
                    View My GitHub Profile
                </a>
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Xavier Boroski</p>
    </footer>

</body>
</html>

