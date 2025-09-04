<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kevin Pimenta - Frontend Developer</title>
    <style>
        :root {
            --primary-color: #64ffda;
            --secondary-color: #8892b0;
            --background-color: #0a192f;
            --light-background: #112240;
            --text-color: #e6f1ff;
            --font-mono: 'Fira Code', monospace;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Calibre', 'Inter', 'San Francisco', 'SF Pro Text', -apple-system, system-ui, sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 2rem;
            max-width: 1000px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            margin-bottom: 3rem;
            padding: 2rem 0;
            border-bottom: 1px solid var(--secondary-color);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            color: var(--primary-color);
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            color: var(--primary-color);
        }
        
        h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        p {
            margin-bottom: 1rem;
            color: var(--secondary-color);
        }
        
        .intro {
            text-align: center;
            margin-bottom: 2rem;
        }
        
        .highlight {
            color: var(--primary-color);
        }
        
        .section {
            background-color: var(--light-background);
            padding: 1.5rem;
            border-radius: 10px;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px -15px rgba(2, 12, 27, 0.7);
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin: 1.5rem 0;
        }
        
        .social-links a {
            color: var(--secondary-color);
            font-size: 1.5rem;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            color: var(--primary-color);
            transform: translateY(-3px);
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .skill-item {
            background-color: rgba(100, 255, 218, 0.1);
            padding: 0.5rem 1rem;
            border-radius: 5px;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            transition: all 0.3s ease;
        }
        
        .skill-item:hover {
            transform: translateY(-3px);
            background-color: rgba(100, 255, 218, 0.2);
        }
        
        .skill-item img {
            width: 24px;
            height: 24px;
        }
        
        .stats {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .fun-fact {
            background-color: rgba(100, 255, 218, 0.1);
            padding: 1rem;
            border-left: 3px solid var(--primary-color);
            margin: 1.5rem 0;
            font-style: italic;
        }
        
        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            
            .skills-container {
                justify-content: center;
            }
            
            .stats {
                flex-direction: column;
                gap: 1rem;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <div class="header">
        <h1>Hi 👋, I'm Kevin Pimenta</h1>
        <h2>A Passionate Frontend Developer from India</h2>
    </div>
    
    <div class="intro">
        <p>I'm a dedicated developer with a passion for creating beautiful, functional web experiences. Currently expanding my skills in deep learning to bridge the gap between frontend development and AI.</p>
    </div>
    
    <div class="section">
        <h3>🌱 What I'm Learning</h3>
        <p>I'm currently deepening my knowledge in <span class="highlight">Deep Learning</span> and exploring how to integrate AI capabilities with frontend applications.</p>
    </div>
    
    <div class="section">
        <h3>👨‍💻 My Projects</h3>
        <p>All of my projects are available on <a href="https://github.com/ke7innnn" style="color: var(--primary-color); text-decoration: none;">GitHub</a>. Feel free to explore, contribute, or provide feedback!</p>
    </div>
    
    <div class="section">
        <h3>📫 How to Reach Me</h3>
        <p>Feel free to reach out to me at <span class="highlight">ke7inpimenta@gmail.com</span> for collaborations, questions, or just to say hello!</p>
    </div>
    
    <div class="section">
        <h3>⚡ Fun Fact</h3>
        <div class="fun-fact">
            <p>"sybau" - because sometimes the best code is written with a little mystery!</p>
        </div>
    </div>
    
    <div class="section">
        <h3>Connect with Me</h3>
        <div class="social-links">
            <a href="https://instagram.com/ke7innn" target="_blank" aria-label="Instagram">
                <i class="fab fa-instagram"></i>
            </a>
            <a href="https://www.youtube.com/c/ke7innnnnnnnnn" target="_blank" aria-label="YouTube">
                <i class="fab fa-youtube"></i>
            </a>
            <a href="https://www.leetcode.com/ke7innn" target="_blank" aria-label="LeetCode">
                <i class="fab fa-python"></i>
            </a>
            <a href="https://github.com/ke7innnn" target="_blank" aria-label="GitHub">
                <i class="fab fa-github"></i>
            </a>
        </div>
    </div>
    
    <div class="section">
        <h3>Languages and Tools</h3>
        <div class="skills-container">
            <div class="skill-item">
                <i class="fab fa-python"></i> Python
            </div>
            <div class="skill-item">
                <i class="fab fa-html5"></i> HTML5
            </div>
            <div class="skill-item">
                <i class="fab fa-css3-alt"></i> CSS3
            </div>
            <div class="skill-item">
                <i class="fab fa-js-square"></i> JavaScript
            </div>
            <div class="skill-item">
                <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="OpenCV"> OpenCV
            </div>
            <div class="skill-item">
                <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow"> TensorFlow
            </div>
            <div class="skill-item">
                <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="Flask"> Flask
            </div>
            <div class="skill-item">
                <i class="fab fa-git-alt"></i> Git
            </div>
            <div class="skill-item">
                <img src="https://www.vectorlogo.zone/logos/mysql/mysql-icon.svg" alt="MySQL"> MySQL
            </div>
            <div class="skill-item">
                <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman"> Postman
            </div>
        </div>
    </div>
    
    <div class="stats">
        <div class="stat-item">
            <h3>10+</h3>
            <p>Projects</p>
        </div>
        <div class="stat-item">
            <h3>5+</h3>
            <p>Technologies</p>
        </div>
        <div class="stat-item">
            <h3>2+</h3>
            <p>Years Learning</p>
        </div>
    </div>
</body>
</html>
