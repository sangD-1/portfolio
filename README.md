# portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sangeeta Dhurve - Personal Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <header>
            <h1>Sangeeta Dhurve</h1>
            <p>Web Development Enthusiast | B.Tech Student</p>
        </header>

        <section id="about">
            <h2>About Me</h2>
            <img src="me.jpg.jpg" alt="sangeeta image" height="300" width="250">

            <p>
                Hello! I'm Sangeeta Dhurve, a second-year B.Tech student passionate about front-end development and UI
                design. I enjoy building responsive and user-friendly websites and am continuously learning new
                technologies to expand my skillset. I'm currently exploring JavaScript frameworks and improving my
                backend knowledge. I'm open to internships, collaborations, and freelance opportunities.
            </p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript (Basics)</li>
                <li>DSA</li>
                <li>Git & GitHub</li>
                <li>Canva (Design)</li>
                <li>C language</li>
                <li>Python</li>
                <li>Java</li>
            </ul>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project-item">
                <h3>Online Food Ordering Platform</h3>
                <img src="food.png" alt="" height="200" width="300">
                <img src="food2.png" alt="" height="200" width="300">
                <p>
                    A user-friendly online food ordering website where customers can browse menus, add items to their
                    cart, and place orders. Built using HTML, CSS, and JavaScript with basic cart functionality using
                    LocalStorage.
                </p>
            </div>

            <div class="project-item">
                <h3>E-Commerce Website</h3>
                <img src="tshirt.png" alt="E-Commerce Screenshot" height="200" width="350">
                <p>
                    Developed a responsive e-commerce site with product listing, cart functionality, and checkout
                    simulation. Technologies used include HTML5, CSS, and JavaScript with LocalStorage.
                </p>
               
            </div>
        </section>

        <section id="resume">
            <h2>Resume</h2>
            <p>Download my resume:</p>
            <a href="SANGEETA resume.pdf" download>Download PDF</a>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:sangeetadhurve128@email.com">sangeetadhurve128@email.com</a></p>
            <p>Phone: +91-9770987704</p>

        </section>

        <footer>
            <p>&copy; 2025 Sangeeta Dhurve. All rights reserved.</p>
        </footer>
    </div>

</body>

</html>


body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #eaf2f8; 
        color: #3f51b5; 
    line-height: 1.6;
}

.container {
    max-width: 960px;
    margin: 20px auto;
    padding: 20px;
    background-color: #ffffff;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
    border-radius: 10px;
}

header {
    text-align: center;
    padding: 30px 20px;
    background-color: #64b5f6; 
    color: white;
    border-radius: 10px 10px 0 0;
    margin: -20px -20px 0 -20px;
}

header h1 {
    margin: 0;
    font-size: 2.8em;
    letter-spacing: 1px;
}

header p {
    font-size: 1.1em;
    opacity: 0.95;
}

section {
    padding: 35px 0;
    border-bottom: 1px solid #e0e0e0;
}

section:last-of-type {
    border-bottom: none;
}

section h2 {
    text-align: center;
    font-size: 2.2em;
    color: #3f51b5; 
    margin-bottom: 25px;
    position: relative;
    padding-bottom: 8px;
}

section h2::after {
    content: '';
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    width: 50px;
    height: 2px;
    background-color: #3f51b5;
}

#about {
    text-align: center;
}

#about img {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 20px;
    border: 4px solid #64b5f6;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

#about p {
    max-width: 650px;
    margin: 0 auto;
    font-size: 1em;
    color: #555;
}

#skills ul {
    list-style: none;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 12px;
}

#skills li {
    background-color: #e3f2fd; 
    padding: 8px 18px;
    border-radius: 20px;
    font-size: 1em;
    color: #3f51b5;
    border: 1px solid #bbdefb;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

#skills li:hover {
    background-color: #64b5f6;
    color: white;
    transform: translateY(-2px);
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.project-item {
    background-color: #f8fcfd; 
    border: 1px solid #e0f2f7; 
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 25px;
    text-align: center;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-item:hover {
    transform: translateY(-4px);
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
}

.project-item img {
    max-width: 100%;
    height: auto;
    border-radius: 6px;
    margin-bottom: 15px;
    border: 1px solid #e0e0e0;
}

.project-item h3 {
    color: #3f51b5;
    margin-top: 0;
    font-size: 1.6em;
}

.project-item p {
    font-size: 0.95em;
    color: #666;
    margin-bottom: 18px;
}

.project-item a {
    display: inline-block;
    background-color: #4caf50; 
    color: white;
    padding: 9px 18px;
    border-radius: 5px;
    text-decoration: none;
    margin: 0 8px;
    transition: background-color 0.3s ease;
    font-size: 0.9em;
}

.project-item a:hover {
    background-color: #43a047;
}

#resume {
    text-align: center;
}

#resume a {
    background-color: #90a4ae; 
    color: white;
    padding: 10px 22px;
    border-radius: 5px;
    text-decoration: none;
    font-size: 1em;
    transition: background-color 0.3s ease;
}

#resume a:hover {
    background-color: #78909c;
}

#contact {
    text-align: center;
}

#contact p {
    font-size: 1em;
    margin-bottom: 8px;
    color: #555;
}

#contact a {
    color: #3f51b5;
    text-decoration: none;
    transition: color 0.3s ease;
}

#contact a:hover {
    text-decoration: underline;
    color: #303f9f;
}

footer {
    text-align: center;
    padding: 18px;
    background-color: #455a64; 
    color: white;
    font-size: 0.85em;
    margin: 0 -20px -20px -20px;
    border-radius: 0 0 10px 10px;
}

@media (max-width: 768px) {
    header h1 {
        font-size: 2.2em;
    }

    section h2 {
        font-size: 1.8em;
    }

    #about img {
        width: 140px;
        height: 140px;
    }

    #skills li {
        padding: 7px 14px;
        font-size: 0.95em;
    }

    .project-item {
        padding: 18px;
    }

    .project-item h3 {
        font-size: 1.4em;
    }

    .project-item a {
        padding: 8px 14px;
        font-size: 0.85em;
    }
}

@media (max-width: 480px) {
    header h1 {
        font-size: 1.8em;
    }

    header p {
        font-size: 0.9em;
    }

    section h2 {
        font-size: 1.6em;
    }

    #about img {
        width: 100px;
        height: 100px;
    }

    #about p {
        font-size: 0.85em;
    }

    #skills ul {
        flex-direction: column;
        align-items: center;
    }

    #skills li {
        width: 90%;
        text-align: center;
    }

    .project-item a {
        display: block;
        margin: 8px auto;
    }
}
