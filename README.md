# Ex01 Portfolio
## Date:

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
home.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <!-- Header -->
  <header class="navbar">
    <h1 class="logo">My Portfolio</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Projects</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <!-- Main Content -->
  <main class="container">
    <h2>Welcome to my portfolio website</h2>

    <p>Hello! I am <strong></strong>G.T.Gowtham.</p>

    <p>
      I am a student studying in Saveetha Engineering College, second year,
      in the department of Internet of Things.
    </p>

    <p>
      I enjoy learning new technologies and improving my technical skills.
    </p>

    <p>
      This portfolio website contains information about me,
      my skills, my projects, and my contact details.
    </p>
    
  </main>

</body>
</html>
~~~
About.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About</title>
    <link rel="stylesheet" href="styles2.css">
</head>
<body>

<header class="navbar">
    <h2 class="logo">My Portfolio</h2>
    <nav>
        <a href="home.html">Home</a>
        <a href="About.html">About</a>
        <a href="project.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="about-container">

    <h1>Skills</h1>

    <div class="card">
        <h4>Programming Skills</h4>
        <ul>
            <li>Basic HTML</li>
            <li>Basic CSS</li>
            <li>Python</li>
            <li>C Programming</li>
        </ul>
    </div>
    
    
    <br>
    <br>

    <div class="card">
        <h4>Tools and Software</h4>
        <ul>
            <li>Visual Studio Code</li>
            <li>Python IDLE</li>
            <li>Canva</li>
            <li>MS Excel</li>
        </ul>
    </div>

    <div class="card info">
        <p>
            I am currently learning Artificial Intelligence and Machine Learning,
            and I am planning to learn Java.
        </p>
    </div>

</section>

</body>
</html>
~~~
project.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Projects</title>
    <link rel="stylesheet" href="style3.css">
</head>
<body>

<header class="navbar">
    <h2 class="logo">My Portfolio</h2>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="project.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="projects-container">

    <h1>Projects</h1>

    <div class="card">
        <ul>
            <li>Dribbble App Clone</li>
            <li>Restaurant Website</li>
            <li>Image Gallery</li>
            <li>Math Server</li>
            <li>Book Cover Design</li>
            <li>UNO Game</li>
            <li>Fitness App</li>
        </ul>
    </div>
    <br>

    <h1>Certificates</h1>

    <div class="card">
        <ul>
            <li>UiPath Certificate</li>
            <li>UX Design for Web Developers</li>
        </ul>
    </div>

</section>

</body>
</html>
~~~
contact.html
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="styles2.css">
</head>
<body>

<header>
    <h2>My Portfolio</h2>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="project.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section>
    <h1>Contact</h1>
    <p>
        Email: mohan.m@gmail.com <br>
        Phone: 9123437831<br>
        linkedin: https://www.linkedin.com/in/mohan.m-b-0872946a/
       
       
    </p>
</section>

</body>
</html>
## OUTPUT
~~~
~~~
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
