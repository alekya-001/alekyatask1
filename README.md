<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Portfolio</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
            margin: 10px;
        }

        #home {
            background-color: #555;
            color: #fff;
            padding: 50px 0;
            text-align: center;
        }

        #about, #projects, #contact {
            background-color: #fff;
            color: #333;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .project-card {
            background-color: #f9f9f9;
            padding: 15px;
            margin: 10px 0;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }

        footer p {
            margin: 0;
        }
    </style>
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
    </header>

    <section id="home">
        <h1>Welcome to My Portfolio</h1>
        <p>Hello, I'm [Your Name], a [Your Profession]</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>[A brief description about yourself, your skills, and experience]</p>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project-card">
            <h3>Project 1</h3>
            <p>[Description of Project 1]</p>
            <a href="#">View Project</a>
        </div>
        <div class="project-card">
            <h3>Project 2</h3>
            <p>[Description of Project 2]</p>
            <a href="#">View Project</a>
        </div>
        <div class="project-card">
            <h3>Project 3</h3>
            <p>[Description of Project 3]</p>
            <a href="#">View Project</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: [your.email@example.com]</p>
        <p>Phone: [Your Phone Number]</p>
        <p>[Your Social Media Links]</p>
    </section>

    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>

</body>
</html>
