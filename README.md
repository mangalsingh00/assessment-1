# assessment-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mangal Singh - Portfolio</title>
</head>
<body>

    <!-- Header / Name -->
    <header>
        <h1>Mangal Singh</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Welcome Section -->
    <section>
        <h2>Welcome to My Portfolio</h2>
        <p>Hello! I am a web development student. This is my personal portfolio website.</p>
    </section>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <!-- Apni image ka path yahan src mein dalein -->
        <img src="avatar.png" alt="Mangal Singh Profile Picture" width="220">
        <p>I am passionate about learning web development and building creative projects.</p>
    </section>

    <!-- My Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <ul>
            <li><strong>Portfolio Website:</strong> A personal one-page website to showcase your bio, skills, and contact details.</li>
            <li><strong>Medium Clone :</strong> A simple blog layout that looks like Medium, built only with HTML and CSS.</li>
            <li><strong>Birthday Card :</strong> A creative greeting card webpage designed with HTML structure and CSS styling.</li>
            <li><strong>User Form:</strong> A form webpage with fields like name, email, and message for practicing form handling.</li>
        </ul>
    </section>

    <!-- Technical Skills Section -->
    <section id="skills">
        <h2>Technical Skills</h2>
        <table border="1" cellpadding="4" cellspacing="0">
            <thead>
                <tr>
                    <th>Skill</th>
                    <th>Level</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>HTML</td>
                    <td>Beginner</td>
                </tr>
                <tr>
                    <td>CSS</td>
                    <td>Beginner</td>
                </tr>
                <tr>
                    <td>JavaScript</td>
                    <td>Learning</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Contact Me Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <p>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>
            </p>
            <p>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>
            </p>
            <p>
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="3" cols="28" placeholder="Enter your message" required></textarea>
            </p>
            <button type="submit">Send</button>
        </form>
    </section>

</body>
</html>
