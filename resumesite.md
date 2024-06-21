<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Resume Website</title>
<style>
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        margin: 0;
        padding: 0;
        background-color: #f0f0f0;
    }
    .container {
        max-width: 800px;
        margin: 20px auto;
        background-color: #fff;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h1, h2, h3 {
        margin-bottom: 10px;
    }
    .section {
        margin-bottom: 20px;
    }
    .section h2 {
        border-bottom: 2px solid #333;
        padding-bottom: 5px;
    }
    .info {
        margin-bottom: 10px;
    }
    .info p {
        margin: 5px 0;
    }
    .work {
        margin-bottom: 20px;
    }
    .work h3 {
        margin-bottom: 5px;
    }
    .skills {
        margin-bottom: 20px;
    }
    .skills ul {
        list-style-type: none;
        padding: 0;
    }
    .skills li {
        margin-bottom: 5px;
    }
</style>
</head>
<body>
<div class="container">
    <header>
        <h1>John Doe</h1>
        <div class="info">
            <p>Email: john.doe@example.com</p>
            <p>Phone: (123) 456-7890</p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/johndoe/">John Doe</a></p>
        </div>
    </header>

    <section class="section">
        <h2>Education</h2>
        <div class="info">
            <h3>Bachelor of Science in Computer Science</h3>
            <p>University of Example, 2014-2018</p>
        </div>
    </section>

    <section class="section">
        <h2>Work Experience</h2>
        <div class="work">
            <h3>Software Engineer</h3>
            <p>ABC Company, 2018-present</p>
            <p>Responsibilities include developing web applications using HTML, CSS, and JavaScript.</p>
        </div>
    </section>

    <section class="section">
        <h2>Skills</h2>
        <div class="skills">
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Responsive Web Design</li>
                <li>Version Control (Git)</li>
                <li>Problem Solving</li>
            </ul>
        </div>
    </section>
</div>
</body>
</html>