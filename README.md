<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E. Mohanaselvan - Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #e63946;
            color: black;
        }
        .header {
            background-color: #a8eb12;
            text-align: center;
            padding: 30px;
            font-size: 28px;
            font-weight: bold;
        }
        .sub-header {
            text-align: center;
            font-size: 18px;
            font-style: italic;
            margin-bottom: 10px;
        }
        .nav {
            text-align: center;
            padding: 15px;
            background-color: #d90429;
        }
        .nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
        }
        .container {
            width: 80%;
            margin: auto;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
        }
        h2 {
            color: #e63946;
        }
        ul {
            padding-left: 20px;
        }
        .resume-btn {
            display: block;
            text-align: center;
            margin-top: 20px;
            padding: 12px;
            background-color: black;
            color: white;
            text-decoration: none;
            font-weight: bold;
            width: 180px;
            margin-left: auto;
            margin-right: auto;
            border-radius: 5px;
            font-size: 16px;
        }
        .footer {
            text-align: center;
            padding: 15px;
            background-color: black;
            color: white;
            margin-top: 30px;
        }
        .contact {
            text-align: center;
            margin-top: 20px;
        }
        .contact a {
            color: #e63946;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="header">E. Mohanaselvan</div>
    <div class="sub-header">Student | Aspiring Developer</div>

    <div class="nav">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </div>

    <div class="container" id="about">
        <h2>About Me</h2>
        <p>I am currently studying BCA second year at Prince Shri Venkateswara Arts and Science College.</p>
    </div>

    <div class="container" id="education">
        <h2>Education</h2>
        <p>Bachelor of Computer Applications (BCA)</p>
        <p>Prince Shri Venkateswara Arts and Science College</p>
    </div>

    <div class="container" id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Java</li>
            <li>Python</li>
        </ul>
    </div>

    <div class="container" id="projects">
        <h2>Projects</h2>
        <ul>
            <li>Projects will be updated soon...</li>
        </ul>
    </div>

    <div class="container" id="resume">
        <h2>Resume</h2>
        <a href="resume.pdf" class="resume-btn" download>Download CV</a>
    </div>

    <div class="container contact" id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:mohanaselvan@example.com">mohanaselvan@example.com</a></p>
        <p>LinkedIn: <a href="#">linkedin.com/in/mohanaselvan</a></p>
        <p>GitHub: <a href="#">github.com/mohanaselvan</a></p>
    </div>

    <div class="footer">© 2024 E. Mohanaselvan</div>

</body>
</html>
