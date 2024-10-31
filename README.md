<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Academic Portfolio</title>
    <style>
        /* Modern and clean design */
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --background-color: #f8f9fa;
            --text-color: #2c3e50;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--background-color);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header styling */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
            margin-bottom: 2rem;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--secondary-color);
        }

        /* Main content styling */
        .hero {
            display: flex;
            gap: 2rem;
            margin-bottom: 3rem;
            align-items: center;
        }

        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
        }

        .section {
            margin-bottom: 3rem;
        }

        h1, h2, h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        .publication {
            margin-bottom: 1.5rem;
            padding: 1rem;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        /* Footer styling */
        footer {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
            margin-top: 3rem;
        }

        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }

        .social-links a {
            color: white;
            text-decoration: none;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .hero {
                flex-direction: column;
                text-align: center;
            }

            nav ul {
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <h1>Your Name</h1>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#research">Research</a></li>
                    <li><a href="#publications">Publications</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <section id="about" class="hero">
            <img src="/api/placeholder/200/200" alt="Your Profile Picture" class="profile-img">
            <div>
                <h2>About Me</h2>
                <p>I am a [Your Position] at [Your Institution] specializing in [Your Field]. My research focuses on [Your Research Interest].</p>
                <p>Currently, I am working on [Current Project or Research Focus].</p>
            </div>
        </section>

        <section id="research" class="section">
            <h2>Research Interests</h2>
            <ul>
                <li>Research Area 1</li>
                <li>Research Area 2</li>
                <li>Research Area 3</li>
            </ul>
        </section>

        <section id="publications" class="section">
            <h2>Selected Publications</h2>
            <div class="publication">
                <h3>Publication Title 1</h3>
                <p>Authors, Journal Name (Year)</p>
                <p>Brief description of the publication and its impact.</p>
            </div>
            <div class="publication">
                <h3>Publication Title 2</h3>
                <p>Authors, Journal Name (Year)</p>
                <p>Brief description of the publication and its impact.</p>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Email: your.email@institution.edu</p>
            <p>Office: Building Name, Room Number</p>
            <p>Institution Name</p>
            <p>Address Line 1</p>
            <p>Address Line 2</p>
            <div class="social-links">
                <a href="#">Google Scholar</a>
                <a href="#">LinkedIn</a>
                <a href="#">Twitter</a>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>© 2024 Your Name. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
