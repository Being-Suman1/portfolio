
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #003366, #004080);
            color: #fff;
        }
        header {
            background: #003366;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 20px;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ffcc00;
        }
        section {
            padding: 50px;
            text-align: center;
        }
        #about {
            background: linear-gradient(135deg, #00509e, #002f6c);
            color: white;
            padding: 50px;
            border-radius: 15px;
            margin: 20px;
            box-shadow: 0 0 20px rgba(0, 80, 158, 0.5);
            pointer-events: none;
        }
        #about img {
            width: 200px;
            height: auto;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        #projects {
            background: rgba(255, 255, 255, 0.1);
            padding: 50px;
            border-radius: 15px;
            margin: 20px;
        }
        .project {
            background: linear-gradient(135deg, #87CEEB, #00BFFF);
            color: white;
            padding: 25px;
            margin: 20px auto;
            width: 60%;
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(135, 206, 235, 0.5);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .project:hover {
            transform: translateY(-8px);
            box-shadow: 0 0 30px rgba(135, 206, 235, 0.8);
        }
        #contact {
            background: linear-gradient(135deg, #003366, #004080);
            padding: 60px;
            border-radius: 15px;
            text-align: center;
        }
        form input, form textarea, form button {
            display: block;
            width: 60%;
            margin: 10px auto;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
        }
        form button {
            background: #87CEEB;
            color: #003366;
            font-weight: bold;
            cursor: pointer;
            border: none;
            transition: background 0.3s;
        }
        form button:hover {
            background: #00BFFF;
        }
        .social-icons {
            text-align: center;
            margin-top: 20px;
        }
        .social-icons a {
            color: white;
            font-size: 28px;
            margin: 0 15px;
            text-decoration: none;
            transition: transform 0.3s;
        }
        .social-icons a:hover {
            transform: scale(1.2);
            color: #ffcc00;
        }
    </style>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <img src="profile.jpg" alt="Profile Picture">
        <h1>Welcome to My Portfolio</h1>
        <p>Hello! I am [Your Name], a web developer passionate about creating stunning websites.</p>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project 1</h3>
            <p>Description of your project.</p>
        </div>
        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <h3>Project 2</h3>
            <p>Description of your project.</p>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
        <div class="social-icons">
            <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
        </div>
    </section>
    
    <script src="script.js"></script>
</body>
</html>
