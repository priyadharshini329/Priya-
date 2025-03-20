<!DOCTYPE html>
<html>
<head>
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #84a6e9;
        }

        header {
            background-color: #941919;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
            position: relative; /* Add this */
        }

        .header-content h1 {
            font-size: 2.5rem;
        }

      nav {
            background-color: #333;
            color: #fff;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        .section-content {
            background-color: #fff;
            padding: 2rem;
            margin: 1rem;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: justify;
        }

        .download-button {
            background-color: #333;
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 20px;
            display: inline-block;
            margin-top: 10px;
            align-self: center;
        }

        .download-button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
        }

        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <h1>PRIYADHARSHINI S</h1>
            <p>Am Software Developer</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education </a></li>
            <li><a href="#skills">
Skills</a></li>
            <li><a href="#projects">projects</a></li>
           
        </ul>
    </nav>

    <section id="about">
        <div class="section-content">
            <h2>About Me</h2>
            <p>I'm <b>Priyadharshini S</b>,currently pursuing a Bachelor of Computer Applications (BCA) at Jeppiaar College of Arts and Science, Padur. I completed my school education at Girls Government Higher Secondary School at Thiruporur, Scoring 71% in my final examination.  My long-term goal is become a Fashion Designing and My Short-time goal is is become a Software Developer.  After completing my degree,I aspire to join a renowned IT company as a software developer, where I can apply my skills and continuously grow in the field of technology.
I have a strong foundation in Python, C++, Java, Advance Java, Datastructure and several other programming languages. I am dedicated to expanding my knowledge by learning more advanced programming languages and staying updated with the latest technological advancements.I am committed to putting in hard work and dedication toward achieving my career goals. Additionally, I plan to pursue a postgraduate degree (PG) to further enhance my expertise and open up greater opportunities in the IT industry.</p>
        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <h2>Education</h2>
            <p>Bachelor of Computer Application-Jeppiaar college of arts and science </p>
            
            
        </div>
    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <ul>
                <li>Python</li>
                <li>C++</li>
                <li>Java</li>
                <li>Datastructure</li>
                <li>HTML</li>
                <li>Advancejava</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="section-content">
            <h2>Projects</h2>
            <ul>
                <li><a href="#">Home Automation System</a></a></li>
                <li><a href="#">Smart Traffic Control with Ambulance Detection</a></li>
                <li><a href="#">Automation in Design</a></li>
                <li><a href="#">Shopping Experience Analysis in Digital Marketing</a></li> 
                <!-- Add more project links here -->
            </ul>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 PRIYADHARSHINI S</p>
    </footer>

    <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
