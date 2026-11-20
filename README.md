Viva La Vida
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kent | My Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            background: #0a0d0b;
            color: white;
            font-family: Arial, sans-serif;
        }

        /* NAVIGATION */
        nav {
            display: flex;
            gap: 25px;
            padding: 20px 5%;
            position: relative;
            z-index: 10;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 17px;
            transition: 0.3s;
        }

        nav a:hover {
            color: #5fbf8a;
        }

        /* HOME SECTION */
        .home {
            min-height: 550px;
            padding: 100px 8%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .hero {
            max-width: 700px;
        }

        .hero h1 {
            font-size: 55px;
            color: #5fbf8a;
            margin-bottom: 15px;
        }

        .hero h2 {
            font-size: 25px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 18px;
            line-height: 1.6;
            color: #c4d0c9;
        }

        /* GENERAL SECTIONS */
        section {
            padding: 80px 8%;
            text-align: center;
        }

        section h2 {
            font-size: 35px;
            color: #5fbf8a;
            margin-bottom: 25px;
        }

        section p {
            font-size: 18px;
            line-height: 1.7;
            color: #c4d0c9;
        }

        /* CARDS */
        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
            margin-top: 30px;
        }

        .card {
            width: 280px;
            min-height: 150px;
            padding: 25px;
            background: #131916;
            border: 1px solid #2f6b4a;
            border-radius: 15px;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
            border-color: #5fbf8a;
        }

        .card h3 {
            color: #8fd4ae;
            margin-bottom: 15px;
        }

        .card p {
            font-size: 15px;
        }

        footer {
            text-align: center;
            padding: 25px;
            color: #7f9488;
        }

        /* MOBILE DISPLAY */
        @media (max-width: 900px) {
            nav {
                justify-content: center;
                flex-wrap: wrap;
            }

            .home {
                min-height: auto;
                padding: 60px 7%;
            }

            .hero h1 {
                font-size: 38px;
            }

            section {
                padding: 60px 6%;
            }
        }
    </style>
</head>

<body>

    <!-- NAVIGATION -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#learning">Learning</a>
        <a href="#midterm">Midterm</a>
        <a href="#final">Final</a>
    </nav>

    <!-- HOME -->
    <div class="home" id="home">
        <div class="hero">
            <h1>Midterms</h1>
            <h2>Welcome to My Portfolio!</h2>
            <p>
                Enter my activity and explore my learning journey,
                laboratory activities, and achievements.
            </p>
        </div>
    </div>

    <!-- ABOUT -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            Hi, I'm Kent! I'm a student on NU Clark who enjoys learning new skills,
            building projects, and growing step by step. This portfolio
            shows my work and progress throughout the course. And hoping that someday
            i'll be able to build my own programming
        </p>
    </section>

    <!-- LEARNING -->
    <section id="learning">
        <h2>My Learning Journey</h2>
        <p>Here are some of the things I have learned so far.</p>

        <div class="cards">
            <div class="card">
                <h3>Java</h3>
                <p>Learning programming fundamentals and object-oriented concepts using Java.</p>
            </div>
            <div class="card">
                <h3>Teamwork</h3>
                <p>Working with classmates and improving through feedback.</p>
            </div>
        </div>
    </section>

    <!-- MIDTERM -->
    <section id="midterm">
        <h2>Midterm</h2>
        <p>My laboratory activities and outputs for the midterm period.</p>

        <div class="cards">
            <div class="card">
                <h3>Laboratory 1</h3>
                <p></p>
            </div>
            <div class="card">
                <h3>Laboratory 2</h3>
                <p>LabTask_2 (1).pdf</p>
            </div>
            <div class="card">
                <h3>Laboratory 3</h3>
                <p>Description of your third midterm activity goes here.</p>
            </div>
        </div>
    </section>

    <!-- FINAL -->
    <section id="final">
        <h2>Final</h2>
        <p>My final outputs and achievements will be posted here.</p>

        <div class="cards">
            <div class="card">
                <h3>Final Project</h3>
                <p>Coming soon.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Kent. All rights reserved.</p>
    </footer>

</body>
</html
