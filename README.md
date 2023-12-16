<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Andreea Dediu - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Andreea Dediu</h1>
        <p>High School Student | Aspiring Entrepreneur</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Andreea Dediu, a passionate high school student with a keen interest in entrepreneurship, marketing, and design.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Leadership</li>
            <li>Communication</li>
            <li>Creativity</li>
            <!-- Add more skills here -->
        </ul>
    </section>

    <section id="education">
        <h2>Education</h2>
        <div class="education-entry">
            <h3>Orizont Lyceum</h3>
            <p>High School, Class 10</p>
        </div>
        <div class="education-entry">
            <h3>Prospera Business School</h3>
            <p>Business Fundamentals Course</p>
        </div>
        <div class="education-entry">
            <h3>Additional Courses</h3>
            <p>Marketing Essentials, Design Thinking, etc.</p>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>

        <div class="project">
            <h3>Family Marketing Initiative</h3>
            <p>Description: Led a project at school to create a family marketing campaign, applying strategic thinking and creativity.</p>
        </div>

        <div class="project">
            <h3>Design Showcase</h3>
            <p>Description: Organized a design exhibition at school, showcasing innovative ideas and collaborative efforts.</p>
        </div>

   

    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:dediu.andreea@mail.ru">dediu.andreea@mail.ru</a></p>
        <p>Phone: 0692 811 112</p>
    </section>

    <footer>
        <p>&copy; 2023 Andreea Dediu. All rights reserved.</p>
    </footer>

</body>
</html>



style.css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* Set your preferred background color */
}

header {
    background-color: #333; /* Set your preferred header background color */
    color: white;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style-type: none;
    padding: 0;
    background-color: #444; /* Set your preferred navigation background color */
    overflow: hidden;
}

nav li {
    float: left;
}

nav a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

nav a:hover {
    background-color: #555; /* Set your preferred navigation hover background color */
}

section {
    margin: 20px;
}

h2 {
    color: #333; /* Set your preferred heading color */
}

h3 {
    color: #555; /* Set your preferred subheading color */
}

.project {
    margin-bottom: 20px;
    padding: 10px;
    background-color: #fff; /* Set your preferred project entry background color */
    border: 1px solid #ddd; /* Set your preferred border color */
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333; /* Set your preferred footer background color */
    color: white;
}
