<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="style\index.css">
    <title>Document</title>
    <!--what is needed:
        1. navigation bar with About, Projects, and Contact (links)
        2. Gallery of projects using flexbox
        3. Info in the about (or placeholder text)
        4. A 'my projects' button that links to page
        5. A 'contact me button that links to page
        6. social media links in the footer section-->
</head>

<body>
    <div class="container">
        <header>
            <nav>
                <div class="animations">
                    <a href="https://github.com/MicheleRegallie/Michele-Renee-Portfolio/blob/6b322c8e89f2eae9f255822cafea83c12bb0c7e8/projects.html" target="_blank">Projects</a>
                    <a href="https://github.com/MicheleRegallie/Michele-Renee-Portfolio/blob/f1a60e244a2fd8f0cda10cfc07025f315223ad34/about.html" target="_blank">About</a>
                    <a href="contact.html" target="_blank">Contact</a>
                </div>
            </nav>
        </header>
    <section class="header-info">
        <div class="header-text">
        <img class="header-image" src="images\michele_regallie_avatar.png" alt="cartoon avatar.">
        <h1>Hi! I'm Michele Renee.</h1>
        </div>
        <h3 class="tagline"> I design, code, and am passionate about creating products that uplift moods.</h3>
        <a href="contact.html"><button class ="contact-btn" type="button">Contact Me</button></a>
    </section>
    <section class="skills-section">
        <h2> Skills</h2>
        <div class="skills">
            <div class="design-skills card">
                <img class="design" src="images\design-image.png" alt="Design Icon.">
                <h3 class="skills-header">Design.</h3>
                <p>I value easy to use and accessible experiences. </p>
                <p>With my designs I use:</p>
                <ul class="tools design-list">
                    <li>Figma</li>
                    <li>Journey Mapping</li>
                    <li>Contextual Inquiry</li>
                    <li>User Research</li>
                    <li>Wireframing</li>
                    <li>Prototyping</li>
                    <li>UI Design</li>
                </ul>
            </div>
            <div class="coding-skills card">
                <img class="code" src="images\code-image.png" alt="Coding Icon.">
                <h3 class="skills-header">Code.</h3>
                <p>I love bringing designs to life by coding from scratch. </p>
                <p>Tools & Coding languages I utilize are:</p>
                <ul class="tools">
                    <li>VS Code</li>
                    <li>Codepen</li>
                    <li>Github</li>
                    <li>Terminal</li>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>Javascript</li>
                </ul>
            </div>
        </div>
    </section>
    <section class="projects">
        <h2> Recent Work </h2>
        <button class="btn projects-btn" type="button">view more projects</button>
        <div class="gallery-1">
            <img class="gallery-img" src="images\Lambda Mobile Dashboard.png" alt="Lambda Mobile Dashboard Project Thumbnail">
            <img class="gallery-img" src="images\foodreaubanner.png" alt="Foodreau Project Thumbnail">
        </div>
        <div class="gallery-1 gallery-animation">
            <h3>Coming Soon!</h3>
            <h3>Coming Soon!</h3>
        </div>
        <div class="gallery-2">
            <img class="gallery-img2" src="images\QFTBbanner.png" alt="Quest for the Best Project Thumbnail.">
        </div>
        <div class="gallery-2 gallery-animation">
            <h3>Coming Soon!</h3>
        </div>
    </section>
    <footer>
        <p> @Michele Renee 2020</p>
        <div class="footer">
            <a href="https://twitter.com/micheleregallie">
                <button class="footer-btn btn" type="button">Twitter</button>
            </a>
            <a href="https://www.linkedin.com/in/micheleregallie/">
                <button class="footer-btn btn" type="button">Linkedin</button>
            </a>
            <a href="https://dribbble.com/micheleregallie" class="footer-btn btn" >
                <button class="footer-btn btn" type="button">Dribbble</button>
            </a>
        </div>
    </footer>
    </div>
</body>
</html>
