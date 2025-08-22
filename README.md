# Ex01 Portfolio
## Date: 20-08-2025

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

# Html:
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav>
                <div class="nav-links">
                    <a href="#about">About</a>
                    <a href="#projects">Projects</a>
                    <a href="#contact">Contact</a>
                </div>
            </nav>
        </div>
        <h1>Hi, I'm Nandhika P</h1>
        <p>App Designer | Web Designer</p>
    </header>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I am passionate about design, and building meaningful web designes and coding. 
           I enjoy to learning new technologies and designing something.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-container">
            <div class="project-card">
                <h3>Portfolio</h3>
                <p>Portfolio website using HTML and CSS.</p>
            </div>
            <div class="project-card">
                <h3>Design Music App</h3>
                <p>I design a music app using Figma. It is similarly like spotify we use to listen music.</p>
            </div>
             <div class="project-card">
                <h3>Online Ticket Booking App</h3>
                <p>I design a Ticket Booking App using Figma. It is used to book ticket for flight, bus, train and even book hotals.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:nandhup859@gmail.com">nandhup859@gmail.com</a></p>
    </section>
</body>
```
# Css
```
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 40px 20px;
}

.nav-links {
    margin-bottom: 20px;
}

.nav-links a {
    color: white; /* link color */
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

.nav-links a:visited {
    color: white; /* visited links stay white */
}

.nav-links a:hover {
    color: lightgray; /* hover effect */
}

section {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    margin-bottom: 15px;
}

.project-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.project-card {
    background: white;
    padding: 20px;
    width: 250px;
    border-radius: 8px;
    box-shadow: 0px 2px 6px rgba(0,0,0,0.1);
}

.project-card h3 {
    margin-top: 0;
}
#contact a {
    color: #333;
    text-decoration: none;
}

#contact a:hover {
    text-decoration: underline;
}
```
## OUTPUT

<img width="1365" height="681" alt="image" src="https://github.com/user-attachments/assets/518b66d5-90e9-4c57-b5c7-0240d42d7afc" />

<img width="1365" height="737" alt="image" src="https://github.com/user-attachments/assets/31b0c185-6938-4e50-90ef-4cc025f34965" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
