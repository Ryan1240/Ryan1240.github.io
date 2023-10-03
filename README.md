# Ryan1240.github.io
My game development portfolio.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ryan1240</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to My Portfolio</h1>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am Ryan and i'm using github to host code and game projects.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of project 1.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of project 2.</p>
        </div>
        <!-- Add more project sections as needed -->
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can reach me at <a href="mailto:your.email@example.com">720771@student.cityofbristol.ac.uk</a>.</p>
    </section>

    <footer>
        <div class="social">
            <a href="https://github.com/Ryan1240" target="_blank"><img src="github-icon.png" alt="GitHub"></a>
            <!-- Add links to your other social media profiles here -->
        </div>
    </footer>
</body>
</html>
/* Reset some default styles */
body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

/* Set a background color and text color */
body {
    background-color: #f0f0f0;
    color: #333;
    font-family: Arial, sans-serif;
}

/* Style the header and navigation menu */
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

/* Style the sections */
section {
    padding: 40px;
}

/* Style the project boxes */
.project {
    margin-bottom: 20px;
    padding: 10px;
    background-color: #fff;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
}

/* Style the social media links */
.social a {
    margin-right: 10px;
    text-decoration: none;
    color: #333;
}

/* Style the footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

footer img {
    width: 30px;
    height: 30px;
}
