# ARSLAN
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
            color: #333;
        }

        header {
            background-color: #007bff;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        header h1, header h2, header p {
            margin: 5px 0;
        }

        section {
            padding: 20px;
            margin: 20px 0;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            margin-top: 0;
        }

        form {
            max-width: 400px;
            margin: 0 auto;
        }

        form label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        form input[type="text"],
        form input[type="email"],
        form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }

        form input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        form input[type="submit"]:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <header>
        <h1>ARSLAN</h1>
        <h2>STUDENT</h2>
        <p>DO SMART WORK</p>
    </header>

    <section id="education">
        <h2>Education</h2>
        <ul>
            <li>Matric:-SMART COLLEGE</li>
            <li>Intermediate:-SMART COLLEGE</li>
            <li>Bachelor's Degree:-UNIVERSITY OF MANAGEMENT AND TECHNOLOGY LAHORE</li>
        </ul>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Skill 1:- C++ </li>
            <li>Skill 2:- HTML</li>
            <li>Skill 3:- SQA</li>
        </ul>
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <p>Proficient in C++ with hands-on experience in developing various projects, including data structures and algorithms implementations. Skilled in Software Quality Assurance methodologies, particularly in testing Fiber-based applications for reliability and performance, ensuring optimal functionality.</p>
    </section>

    <section id="projects">
        <h2>Complete Projects</h2>
        <ul>
            <li>Project 1:- ONLINE SHOPPING SYSTEM IN C++</li>
            <li>Project 2:- TIC TAC TOE GAME</li>
            <li>Project 3;- ONLINE RESTURANT SYSTEM IN C++</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Form</h2>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Submit">
        </form>
    </section>

</body>
</html>
