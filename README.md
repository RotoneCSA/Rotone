
#Portfolio
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My High-Tech Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: radial-gradient(circle at top, #0f2027, #000000);
            color: #e0e0e0;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            box-shadow: 0 0 20px #00ffff55;
        }

        header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #00ffff;
            box-shadow: 0 0 25px #00ffff;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 2.5em;
            margin: 10px 0 5px;
            letter-spacing: 2px;
        }

        header p {
            color: #00ffff;
            font-size: 1.1em;
        }

        section {
            margin: 30px auto;
            max-width: 900px;
            background: rgba(255, 255, 255, 0.05);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 0 15px #00ffff22;
        }

        h2 {
            color: #00ffff;
            border-bottom: 2px solid #00ffff;
            padding-bottom: 10px;
            letter-spacing: 1px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li::before {
            content: "▹ ";
            color: #00ffff;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 0.9em;
        }

        a {
            color: #00ffff;
            text-decoration: none;
        }

        a:hover {
            text-shadow: 0 0 5px #00ffff;
        }
    </style>
</head>
<body>

    <!-- HEADER WITH PROFILE IMAGE -->
    <header>
        <!-- Replace profile.jpg with your own image file -->
        <img src="https://uploads.onecompiler.io/44a2gqpwf/44a2gnwqu/1000008755.jpg" />
        <h1>Your Name</h1>
        <p>High-Tech | Future Web Developer</p>
    </header>

    <!-- ABOUT ME -->
    <section>
        <h2>About Me</h2>
        <p>
            I am a passionate student learning modern web technologies. 
            I enjoy building clean, futuristic, and user-friendly interfaces 
            while continuously improving my technical skills.
        </p>
    </section>

    <!-- SKILLS -->
    <section>
        <h2>Skills</h2>
        <ul>
            <li>HTML5 & CSS3</li>
            <li>Responsive Web Design</li>
            <li>Basic JavaScript</li>
            <li>UI / UX Fundamentals</li>
        </ul>
    </section>

    <!-- CONTACT -->
    <section>
        <h2>Contact</h2>
        <p>Email: yourname@email.com</p>
        <p>Facebook: <a href="#">facebook.com/yourprofile</a></p>
        <p>GitHub: <a href="#">github.com/yourusername</a></p>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>© 2026 Your Name | High-Tech Portfolio</p>
    </footer>

</body>
</html>
