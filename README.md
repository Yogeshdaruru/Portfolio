# Ex01 Portfolio

## Date: 02-02-2026

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
## HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header / Hero Section -->
    <header class="hero">
        <div class="container">
            <h1>Hi, I'm <span class="highlight">YOGESH DHARURU</span></h1>
            <p class="tagline">Web Developer | Designer | Tech Enthusiast</p>
            <a href="#projects" class="btn">View My Work</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>
                I am a B.Tech (IT) student passionate about creating interactive, responsive websites
                and learning the latest web technologies. I enjoy solving problems and bringing ideas to life
                through clean code and creative design.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section bg-light">
        <div class="container">
            <h2>Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">HTML5</div>
                <div class="skill-card">CSS3</div>
                <div class="skill-card">C</div>
                <div class="skill-card">Python</div>
                <div class="skill-card">Git & GitHub</div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section">
        <div class="container">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Portfolio Website</h3>
                    <p>A Personal Portfolio To Showcase My Skills and Projects.</p>
                </div>
                <div class="project-card">
                    <h3>Snake Game</h3>
                    <p>A Fun Game To Play Without Age Limits.</p>
                </div>
                <div class="project-card">
                    <h3>Soil Monitor</h3>
                    <p>A Sensor Based Soil Monitor For IOT Board.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <footer class="footer">
        <p>Contact: <a>yogeshdharuru@gmail.com</a></p>
        <p>&copy; 2025 YOGESH DHARURU</p>
    </footer>

</body>
</html>
```
## CSS
```
/* General Styles */
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    line-height: 1.6;
    color: #333;
}

/* Container */
.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

/* Hero Section */
.hero {
    background: linear-gradient(to right, #0072ff, #00c6ff);
    color: white;
    text-align: center;
    padding: 5rem 1rem;
}

.hero h1 {
    font-size: 2.5rem;
}

.highlight {
    color: #ffea00;
}

.tagline {
    margin: 1rem 0;
    font-size: 1.2rem;
}

.btn {
    display: inline-block;
    background: white;
    color: #0072ff;
    padding: 0.7rem 1.5rem;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    transition: background 0.3s;
}

.btn:hover {
    background: #ffea00;
    color: black;
}

/* Section */
.section {
    padding: 3rem 0;
}

.bg-light {
    background: #f4f4f4;
}

/* Skills Grid */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 1rem;
    margin-top: 1.5rem;
}

.skill-card {
    background: white;
    padding: 1rem;
    text-align: center;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Projects Grid */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
    margin-top: 1.5rem;
}

.project-card {
    background: white;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Footer */
.footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
}

.footer a {
    color: #00c6ff;
    text-decoration: none;
}
```

## OUTPUT

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/1d900f31-6dbf-4443-b0d6-0e4b7cfc3c40" />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/c9859ed4-79fb-4b14-834b-3d6675be6dba" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
