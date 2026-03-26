# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

#### index.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website - Sam Kumar</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="logo">Port<span class="highlight">folio</span></div>
            <ul class="nav-menu">
                <li><a href="#home" class="nav-link">Home</a></li>
                <li><a href="#about" class="nav-link">About</a></li>
                <li><a href="#skills" class="nav-link">Skills</a></li>
                <li><a href="#education" class="nav-link">Education</a></li>
                <li><a href="#experience" class="nav-link">Experience</a></li>
                <li><a href="#contact" class="nav-link">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <span class="welcome-text">Welcome to Sam.com</span>
                    <h1>Shailesh <span class="highlight">Kumar</span></h1>
                    <h2>I'm a passionate web developer from Chennai</h2>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-github"></i></a>
                    </div>
                </div>
                <div class="hero-image">
                    <img src="images/main-bg.png" alt="Sam Kumar">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="about-content">
                <div class="about-image">
                    <img src="images/about-us.png" alt="About Me">
                </div>
                <div class="about-text">
                    <h2 class="section-title">About Me</h2>
                    <h3>I am available for Web Design Projects</h3>
                    <p>I'm a passionate and curious individual who loves exploring new ideas and turning them into reality. With a strong focus on learning and growth, I enjoy solving problems, building creative projects, and connecting with people who share similar interests.</p>
                    
                    <div class="info-grid">
                        <div class="info-item">
                            <strong>Name:</strong> Shailesh Kumar
                        </div>
                        <div class="info-item">
                            <strong>Email:</strong> info@example.com
                        </div>
                        <div class="info-item">
                            <strong>Birthday:</strong> 03 March, 2000
                        </div>
                        <div class="info-item">
                            <strong>Study:</strong> Chicago University
                        </div>
                        <div class="info-item">
                            <strong>Phone:</strong> (+12) 3456-789-012
                        </div>
                        <div class="info-item">
                            <strong>City:</strong> New York, USA
                        </div>
                        <div class="info-item">
                            <strong>Freelancer:</strong> Available
                        </div>
                        <div class="info-item">
                            <strong>Website:</strong> www.sam.com
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">My Skills</h2>
            <div class="skills-container">
                <!-- Linear Progress Bars -->
                <div class="linear-skills">
                    <div class="skill-item">
                        <div class="skill-info">
                            <span class="skill-name">HTML</span>
                            <span class="skill-percentage">95%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 95%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-info">
                            <span class="skill-name">CSS</span>
                            <span class="skill-percentage">91%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 91%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-info">
                            <span class="skill-name">JavaScript</span>
                            <span class="skill-percentage">85%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-info">
                            <span class="skill-name">React JS</span>
                            <span class="skill-percentage">79%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 79%"></div>
                        </div>
                    </div>
                </div>

                <!-- Circular Progress Bars -->
                <div class="circular-skills">
                    <div class="circular-item">
                        <div class="circular-progress" style="--percentage: 65">
                            <svg viewBox="0 0 100 100">
                                <circle cx="50" cy="50" r="45" class="circle-bg"></circle>
                                <circle cx="50" cy="50" r="45" class="circle-progress"></circle>
                            </svg>
                            <div class="circular-text">Java</div>
                        </div>
                    </div>
                    
                    <div class="circular-item">
                        <div class="circular-progress" style="--percentage: 85">
                            <svg viewBox="0 0 100 100">
                                <circle cx="50" cy="50" r="45" class="circle-bg"></circle>
                                <circle cx="50" cy="50" r="45" class="circle-progress"></circle>
                            </svg>
                            <div class="circular-text">Python</div>
                        </div>
                    </div>
                    
                    <div class="circular-item">
                        <div class="circular-progress" style="--percentage: 65">
                            <svg viewBox="0 0 100 100">
                                <circle cx="50" cy="50" r="45" class="circle-bg"></circle>
                                <circle cx="50" cy="50" r="45" class="circle-progress"></circle>
                            </svg>
                            <div class="circular-text">C</div>
                        </div>
                    </div>
                    
                    <div class="circular-item">
                        <div class="circular-progress" style="--percentage: 85">
                            <svg viewBox="0 0 100 100">
                                <circle cx="50" cy="50" r="45" class="circle-bg"></circle>
                                <circle cx="50" cy="50" r="45" class="circle-progress"></circle>
                            </svg>
                            <div class="circular-text">SQL</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
<section id="education" class="education">
    <div class="container">
        <h2 class="section-title">Education</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-date">2005-2008</div>
                <div class="timeline-content">
                    <h3>Master in Computer Engineering</h3>
                    <p>Harvard University</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">2005-2008</div>
                <div class="timeline-content">
                    <h3>Doctor in Computer Engineering</h3>
                    <p>Stanford University</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">2005-2008</div>
                <div class="timeline-content">
                    <h3>Bachelor in Computer Engineering</h3>
                    <p>University of Oxford</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">2005-2008</div>
                <div class="timeline-content">
                    <h3>Polytechnic in Computer Engineering</h3>
                    <p>University of Cambridge</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Experience Section -->
<section id="experience" class="experience">
    <div class="container">
        <h2 class="section-title">Experience</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-date">2023 - Current</div>
                <div class="timeline-content">
                    <h3>Front End Developer</h3>
                    <p>Apple Inc Company</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">2021-2023</div>
                <div class="timeline-content">
                    <h3>Graphic Design Student Portfolio Websites Template</h3>
                    <p>Google Inc Company</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">2019-2021</div>
                <div class="timeline-content">
                    <h3>Front End Developer</h3>
                    <p>Amazon Ecommerce Company</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">2017-2019</div>
                <div class="timeline-content">
                    <h3>UI / UX Designer</h3>
                    <p>Microsoft Adobe Company</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="main-section bg-lightgrey">
    <div class="container">
        <h2 class="heading-text">Contact</h2>
        <div class="contact-container">
            <div class="contact-form">
                <form>
                    <input type="text" placeholder="Full Name.." required>
                    <input type="email" placeholder="Full Email Id.." required>
                    <input type="tel" placeholder="Full Mobile No.." required>
                    <input type="text" placeholder="Enter Address.." required>
                    <textarea placeholder="Address" rows="4"></textarea>
                    <button type="submit" class="submit-btn">Submit</button>
                </form>
            </div>
            <div class="contact-info">
                <div class="contact-item">
                    <i class="fas fa-phone"></i>
                    <span>Phone</span>
                    <span>+91 99 26 661 418</span>
                </div>
                <div class="contact-item">
                    <i class="fas fa-envelope"></i>
                    <span>Email</span>
                    <span>support@dezven.com</span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="footer">
    <div class="container">
        <p>&copy Copyright 2025 Sam.com Website Template. All Rights Reserved</p>
    </div>
</footer>
</body>
</html>

```
#### style.css

```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #000;
    color: #fff;
    line-height: 1.6;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.highlight {
    color: #ffbf35;
}

/* Navigation */
.navbar {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(0, 0, 0, 0.9);
    z-index: 1000;
    padding: 20px 0;
}

.navbar .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 2rem;
    font-weight: bold;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 30px;
}

.nav-link {
    color: #fff;
    text-decoration: none;
    font-size: 1.1rem;
    transition: color 0.3s;
}

.nav-link:hover {
    color: #ffbf35;
}

/* Hero Section */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    padding-top: 80px;
}

.hero-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
    align-items: center;
}

.welcome-text {
    color: #ffbf35;
    font-size: 1.2rem;
}

.hero-text h1 {
    font-size: 3.5rem;
    margin: 10px 0;
}

.hero-text h2 {
    font-size: 1.5rem;
    font-weight: 400;
    margin-bottom: 30px;
}

.social-links {
    display: flex;
    gap: 15px;
    margin-top: 30px;
}

.social-links a {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50px;
    height: 50px;
    border: 2px solid #ffbf35;
    border-radius: 50%;
    color: #ffbf35;
    text-decoration: none;
    font-size: 1.2rem;
    transition: all 0.3s;
}

.social-links a:hover {
    background: #ffbf35;
    color: #000;
}

.hero-image img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

/* About Section */
.about {
    padding: 100px 0;
    background: #111;
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
    align-items: center;
}

.about-image img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

.section-title {
    font-size: 2.5rem;
    color: #ffbf35;
    margin-bottom: 20px;
}

.about-text h3 {
    font-size: 1.5rem;
    margin-bottom: 20px;
    color: #ccc;
}

.about-text p {
    margin-bottom: 30px;
    line-height: 1.8;
    color: #aaa;
}

.info-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 15px;
}

.info-item {
    color: #aaa;
}

.info-item strong {
    color: #fff;
}

/* Skills Section */
.skills {
    padding: 100px 0;
}

.skills-container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
    margin-top: 50px;
}

/* Linear Progress Bars */
.linear-skills {
    display: flex;
    flex-direction: column;
    gap: 30px;
}

.skill-item {
    background: #111;
    padding: 20px;
    border-radius: 10px;
}

.skill-info {
    display: flex;
    justify-content: space-between;
    margin-bottom: 10px;
}

.skill-name {
    font-weight: bold;
    font-size: 1.1rem;
}

.skill-percentage {
    color: #ffbf35;
    font-weight: bold;
}

.skill-bar {
    height: 8px;
    background: #333;
    border-radius: 4px;
    overflow: hidden;
    position: relative;
}

.skill-progress {
    height: 100%;
    background: #ffbf35;
    border-radius: 4px;
    position: relative;
    animation: fillBar 2s ease-in-out;
}

@keyframes fillBar {
    from {
        width: 0;
    }
}

/* Circular Progress Bars */
.circular-skills {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
}

.circular-item {
    display: flex;
    justify-content: center;
}

.circular-progress {
    position: relative;
    width: 150px;
    height: 150px;
}

.circular-progress svg {
    width: 100%;
    height: 100%;
    transform: rotate(-90deg);
}

.circle-bg {
    fill: none;
    stroke: #333;
    stroke-width: 8;
}

.circle-progress {
    fill: none;
    stroke: #ffbf35;
    stroke-width: 8;
    stroke-linecap: round;
    stroke-dasharray: 283;
    stroke-dashoffset: 283;
    animation: fillCircle 2s ease-in-out forwards;
}

@keyframes fillCircle {
    to {
        stroke-dashoffset: calc(283 - (283 * var(--percentage)) / 100);
    }
}

.circular-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 1rem;
    font-weight: bold;
    color: #ffbf35;
}

/* Responsive Design */
@media (max-width: 768px) {
    .hero-content,
    .about-content,
    .skills-container {
        grid-template-columns: 1fr;
    }
    
    .nav-menu {
        display: none;
    }
    
    .hero-text h1 {
        font-size: 2.5rem;
    }
    
    .circular-skills {
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Education & Experience Sections */
.education, .experience {
    padding: 100px 0;
}

.education {
    background: #111;
}

/* Timeline Design */
.timeline {
    position: relative;
    max-width: 800px;
    margin: 50px auto 0;
}

.timeline::before {
    content: '';
    position: absolute;
    left: 50%;
    top: 0;
    bottom: 0;
    width: 2px;
    background: #ffbf35;
    transform: translateX(-50%);
}

.timeline-item {
    position: relative;
    margin-bottom: 50px;
    display: flex;
    align-items: center;
}

.timeline-item:nth-child(odd) {
    flex-direction: row;
    text-align: right;
}

.timeline-item:nth-child(even) {
    flex-direction: row-reverse;
    text-align: left;
}

.timeline-date {
    flex: 1;
    padding: 0 30px;
    font-weight: bold;
    color: #ffbf35;
    font-size: 1.1rem;
}

.timeline-content {
    flex: 1;
    padding: 20px 30px;
    background: #222;
    border-radius: 10px;
    position: relative;
    margin: 0 20px;
}

.timeline-content::before {
    content: '';
    position: absolute;
    top: 50%;
    width: 0;
    height: 0;
    border: 10px solid transparent;
    transform: translateY(-50%);
}

.timeline-item:nth-child(odd) .timeline-content::before {
    right: -20px;
    border-left-color: #222;
}

.timeline-item:nth-child(even) .timeline-content::before {
    left: -20px;
    border-right-color: #222;
}

.timeline-content h3 {
    color: #fff;
    font-size: 1.3rem;
    margin-bottom: 5px;
}

.timeline-content p {
    color: #aaa;
    font-size: 1rem;
}

/* Timeline Dots */
.timeline-item::after {
    content: '';
    position: absolute;
    left: 50%;
    top: 50%;
    width: 15px;
    height: 15px;
    background: #ffbf35;
    border-radius: 50%;
    transform: translate(-50%, -50%);
    z-index: 1;
}

/* Responsive Timeline */
@media (max-width: 768px) {
    .timeline::before {
        left: 20px;
    }
    
    .timeline-item {
        flex-direction: row !important;
        text-align: left !important;
        padding-left: 50px;
    }
    
    .timeline-date {
        flex: none;
        width: 100%;
        padding: 0;
        margin-bottom: 10px;
    }
    
    .timeline-content {
        margin: 0;
    }
    
    .timeline-content::before {
        left: -20px !important;
        right: auto !important;
        border-right-color: #222 !important;
        border-left-color: transparent !important;
    }
    
    .timeline-item::after {
        left: 20px;
        transform: translate(-50%, -50%);
    }
}

.contact-container {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 50px;
    margin-top: 50px;
}

.contact-form form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-form input,
.contact-form textarea {
    padding: 12px;
    border: 1px solid #333;
    background: #111;
    color: #fff;
    border-radius: 5px;
    font-size: 16px;
    font-family: Arial, sans-serif;
}

.contact-form input::placeholder,
.contact-form textarea::placeholder {
    color: #888;
}

.submit-btn {
    background: #ffbf35;
    color: #000;
    border: none;
    padding: 12px 30px;
    border-radius: 5px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
    transition: background 0.3s;
    margin-top: 10px;
}

.submit-btn:hover {
    background: #e6ac30;
}

.contact-info {
    display: flex;
    flex-direction: column;
    gap: 25px;
}

.contact-item {
    display: flex;
    flex-direction: column;
    gap: 5px;
}

.contact-item i {
    color: #ffbf35;
    font-size: 20px;
    margin-bottom: 5px;
}

.contact-item span:first-of-type {
    color: #fff;
    font-weight: bold;
}

.contact-item span:last-of-type {
    color: #ccc;
}

.footer {
    background: #111;
    padding: 20px 0;
    text-align: center;
    border-top: 1px solid #333;
    margin-top: 50px;
}

.footer p {
    color: #888;
    font-size: 14px;
    margin: 0;
}

@media (max-width: 768px) {
    .contact-container {
        grid-template-columns: 1fr;
    }
}
```



## OUTPUT

<img width="1869" height="858" alt="image" src="https://github.com/user-attachments/assets/6a1cd4c7-8479-4295-a4bb-0813a4190a57" />

<img width="1891" height="845" alt="image" src="https://github.com/user-attachments/assets/db36165b-f7ef-46ee-aba9-e00f69540287" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
