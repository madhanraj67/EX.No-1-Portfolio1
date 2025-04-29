# Ex01 Portfolio
## Date:04-03-2025

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
index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Portfolio</title>
    <link rel="stylesheet" href="color.css">

</head>
<body>

    <header>
        <h1>My Portfolio</h1>
        <nav>
            <a href="#about">About</a>
            <a href="project.html" >Projects</a>
            <a href="skills.html" >Skills</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <img src="3354.jpg" alt="Profile Picture">
            <p><strong>Name:</strong> MADHANRAJ P</p>
            <p>Hello! I am a web developer passionate about creating beautiful and functional websites. I enjoy learning new technologies and improving my skills. I specialize in front-end development and have experience working with modern frameworks and tools.</p>
        </section>
        </div>
        
       
        
</body>
</html>
```

project.hml
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="color.css">
    <title>PROJECT</title>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <a href="intex.html">About</a>
            <a href="project.html" >Projects</a>
            <a href="skills.html" >Skills</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <div class="container">
    <section id="projects" class="section">
        <h2>Projects</h2>
        <ul>
            <li><strong>Project 1:</strong> A responsive website for a local business, built with HTML, CSS, and JavaScript.</li>
            <li><strong>Project 2:</strong> A personal blog using modern web technologies like React and Node.js.</li>
            <li><strong>Project 3:</strong> A portfolio showcasing my work and skills, designed with a focus on user experience.</li>
        </ul>
    </section>
</div>
</body>
</html>
```

skills.hml
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skills</title>
    <link rel="stylesheet" href="color.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <a href="intex.html">About</a>
            <a href="project.html" >Projects</a>
            <a href="skills.html" >Skills</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section id="skills" class="section">
        <h2>Skills</h2>
        <div class="container">
        <div class="skills">
            <div><strong>HTML5</strong></div>
            <div><strong>CSS</strong></div>
            <div><strong>JavaScript</strong></div>
            <div><strong>React</strong></div>
            <div><strong>Node.js</strong></div>
            <div><strong>Git & GitHub</strong></div>
        </div>
    </section>
</div>
</body>
</html>
```

contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="color.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <a href="intex.html">About</a>
            <a href="project.html" >Projects</a>
            <a href="skills.html" >Skills</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section id="contact" class="section">
        <h2>Contact</h2>
        <p>Email 📩:<a href="mailto:me@gmail.com">admin@gmail.com</a></p>
        <p>Phone 📞: <a href="tel:+912345678901">+91 9876543210</a></p>
        <p>Instagram 🅾: <a href="https://www.instagram.com/" target="_blank">Instagram.com/in/yourprofile</a></p>
    </section>
</div>
<footer>
    <p>&copy; 2025 My Portfolio | <a href="#about">Back to Top</a></p>
</footer>

</body>
</html>
```

color.css
```

        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(90deg, #333, #555);
            color: #fff;
            padding: 1.5rem 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            margin: 0;
            font-size: 2.8rem;
            letter-spacing: 2px;
        }
        nav {
            margin: 1rem 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #ffcc00;
        }
        .container {
            max-width: 1100px;
            margin: 2rem auto;
            background: #fff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .section {
            margin-bottom: 3rem;
        }
        .section h2 {
            margin-bottom: 1rem;
            color: #333;
            font-size: 2rem;
            border-bottom: 3px solid #333;
            display: inline-block;
            padding-bottom: 0.5rem;
        }
        .section p, .section ul {
            font-size: 1.1rem;
        }
        .section ul {
            list-style: none;
            padding: 0;
        }
        .section ul li {
            background: #f9f9f9;
            margin: 0.5rem 0;
            padding: 0.8rem;
            border-left: 5px solid #333;
            transition: background 0.3s ease;
        }
        .section ul li:hover {
            background: #f4f4f4;
        }
        img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            display: block;
            margin: 1.5rem auto;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        .skills div {
            flex: 1 1 calc(33.333% - 1rem);
            background: #f4f4f4;
            padding: 1rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .skills div:hover {
            background: #eaeaea;
        }
        footer {
            
            border-radius: 5px;
            text-align: center;
            padding: 1.5rem 0;
            background: #333;
            color: #fff;
            margin-top: 2rem;
        }
        footer p {
            margin: 0;
            font-size: 0.9rem;
        }
        footer a {
            color: #ffcc00;
            text-decoration: none;
            font-weight: bold;
        }
        footer a:hover {
            text-decoration: underline;
        }
```


## OUTPUT
![Screenshot (36)](https://github.com/user-attachments/assets/cb692e54-a800-4c77-8b16-ab695a25d3b4)
![Screenshot (40)](https://github.com/user-attachments/assets/4c8c0ba6-9fa4-4fc5-bb85-8268f26ab9ec)
![Screenshot (38)](https://github.com/user-attachments/assets/757a2fc3-f7a6-43b4-991e-59d422e7f336)
![Screenshot (39)](https://github.com/user-attachments/assets/830a2b0d-2e6c-4d56-b38b-59d9f04611c4)





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
