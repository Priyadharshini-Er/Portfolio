# Ex01 Portfolio
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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Priyadharshini Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f4f4f4;
            color: #333;
        }

        header {
            background: #0D0DFF;
            color: white;
            padding: 15px 0;
            position: sticky;
            top: 0;
        }

        nav {
            display: flex;
            justify-content: space-between;
            width: 80%;
            margin: auto;
        }

        nav h2 {
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        .hero {
            background: #0D0DFF;
            color: white;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 40px;
        }

        .hero p {
            margin-top: 10px;
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background: white;
            color: #0D0DFF;
            text-decoration: none;
            border-radius: 5px;
        }

        .container {
            width: 80%;
            margin: auto;
        }

        .skills, .projects {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .card {
            background: white;
            padding: 20px;
            margin: 10px;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        footer {
            background: #0D0DFF;
            color: white;
            text-align: center;
            padding: 15px;
        }

        @media(max-width: 768px) {
            nav {
                flex-direction: column;
                align-items: center;
            }

            .skills, .projects {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>

<body>

<header>
    <nav>
        <h2>MyPortfolio</h2>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <h1>Hello, I'm Priya</h1>
    <p>Aspiring Cybersecurity & Web Developer</p>
    <a href="#contact" class="btn">Hire Me</a>
</section>

<section id="about">
    <div class="container">
        <h2>About Me</h2>
        <p>I am passionate about cybersecurity and web development. I love building secure and modern web applications.</p>
    </div>
</section>

<section id="skills">
    <div class="container">
        <h2>Skills</h2>
        <div class="skills">
            <div class="card">HTML</div>
            <div class="card">CSS</div>
            <div class="card">JavaScript</div>
            <div class="card">Cybersecurity Basics</div>
        </div>
    </div>
</section>

<section id="projects">
    <div class="container">
        <h2>Projects</h2>
        <div class="projects">
            <div class="card">
                <h3>Cyber Triage Tool</h3>
                <p>Digital forensic investigation tool.</p>
            </div>
            <div class="card">
                <h3>Task Manager</h3>
                <p>Task management web app with local storage.</p>
            </div>
        </div>
    </div>
</section>

<section id="contact">
    <div class="container">
        <h2>Contact</h2>
        <p>Email: your@email.com</p>
    </div>
</section>

<footer>
    <p>© 2026 Priya | All Rights Reserved</p>
</footer>

</body>
</html>
```

## OUTPUT
![WhatsApp Image 2026-03-22 at 10 51 41 PM](https://github.com/user-attachments/assets/e3738d98-5401-4777-9371-fb76c4d9dc1d)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
