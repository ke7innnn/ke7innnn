# 🔥 Welcome to My World 🔥

![Futuristic Banner](https://example.com/your-futuristic-header-gif.gif)

---

## 🚀 About Me

I'm a **Full-time Code Wizard** with a passion for creating digital magic.
- 🤖 AI/ML Enthusiast | Backend Dev | Professional Bug Collector
- 🎮 Competitive Gamer, Meme Connoisseur & Digital Nomad
- 🥶 Writing spaghetti code but serving it like Michelin star cuisine

<br>

| ☕ Coffee Cups | 📂 Projects Completed | 🐛 Bugs Created | ✅ Bugs Fixed |
| :------------- | :-------------------- | :------------- | :------------ |
| 1274           | 42                    | 999            | 427           |

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=react-dark&bg_color=050510&hide_border=true&area=true" alt="Activity Graph" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=YOUR_USERNAME&theme=tokyonight" alt="Streak Stats" />
</div>

---

## 💻 Tech Stack

- **Languages:** Python, JavaScript
- **Frameworks:** React, Node.js
- **Databases:** MongoDB, MySQL
- **Tools:** Docker, AWS, Git, Linux

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 😄 Fun Zone

> "I commit my life mistakes with `git push -f`"

<br>

<div align="center">
  <img src="https://media.giphy.com/media/3oKIPwoeGErMmaI43C/giphy.gif" alt="Coding Meme" width="300" />
  <img src="https://media.giphy.com/media/26xBP3lPAFz9FqF0w/giphy.gif" alt="Debugging Meme" width="300" />
</div>

---

## 🤝 Let's Connect

<div align="center">
  <a href="https://twitter.com/YOUR_HANDLE"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
  <a href="https://linkedin.com/in/YOUR_HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://discord.gg/YOUR_INVITE"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  <a href="mailto:your@email.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/YOUR_USERNAME"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
</div>

---

<div align="center">
  <br>
  <p>🔥 Thanks for scrolling all the way down 🔥</p>
  <p>Now go check out my repos 😎</p>
</div>
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        /* Header Styles */
        .header {
            text-align: center;
            padding: 4rem 0;
            position: relative;
            overflow: hidden;
        }
        
        .glitch-wrapper {
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 2rem;
        }
        
        .glitch {
            position: relative;
            font-size: 4rem;
            font-weight: 900;
            color: #fff;
            letter-spacing: 3px;
            animation: shift 4s ease-in-out infinite alternate;
        }
        
        .glitch::before,
        .glitch::after {
            content: attr(data-text);
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        
        .glitch::before {
            animation: glitch-animation 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94) both infinite;
            color: var(--neon-cyan);
            z-index: -1;
        }
        
        .glitch::after {
            animation: glitch-animation 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94) reverse both infinite;
            color: var(--neon-pink);
            z-index: -2;
        }
        
        @keyframes glitch-animation {
            0% { transform: translate(0); }
            20% { transform: translate(-5px, 5px); }
            40% { transform: translate(-5px, -5px); }
            60% { transform: translate(5px, 5px); }
            80% { transform: translate(5px, -5px); }
            100% { transform: translate(0); }
        }
        
        @keyframes shift {
            0%, 40%, 44%, 58%, 61%, 65%, 69%, 73%, 100% {
                transform: skewX(0deg);
            }
            41% { transform: skewX(10deg); }
            42% { transform: skewX(-10deg); }
            59% { transform: skewX(40deg) skewY(10deg); }
            60% { transform: skewX(-40deg) skewY(-10deg); }
            63% { transform: skewX(10deg) skewY(-5deg); }
            70% { transform: skewX(-50deg) skewY(-20deg); }
            71% { transform: skewX(10deg) skewY(-10deg); }
        }
        
        .typing-container {
            margin: 2rem 0;
            min-height: 80px;
        }
        
        .typing-text {
            font-size: 1.8rem;
            background: linear-gradient(90deg, var(--neon-cyan), var(--neon-pink), var(--neon-green));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        /* Section Styles */
        .section {
            background: var(--card-bg);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 2rem;
            margin-bottom: 3rem;
            backdrop-filter: blur(10px);
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.2);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .section::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            z-index: -1;
            background: linear-gradient(45deg, var(--neon-cyan), transparent, var(--neon-pink), transparent, var(--neon-green));
            background-size: 400%;
            border-radius: 15px;
            animation: glowing 20s linear infinite;
        }
        
        @keyframes glowing {
            0% { background-position: 0 0; }
            50% { background-position: 400% 0; }
            100% { background-position: 0 0; }
        }
        
        .section:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 30px rgba(0, 255, 255, 0.4);
        }
        
        .section-title {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            color: var(--neon-cyan);
        }
        
        .section-title i {
            margin-right: 15px;
            font-size: 1.8rem;
        }
        
        /* Stats Grid */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .stat-card {
            background: rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            padding: 1.5rem;
            text-align: center;
            transition: all 0.3s ease;
        }
        
        .stat-card:hover {
            transform: scale(1.05);
            box-shadow: 0 0 15px var(--neon-pink);
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
            background: linear-gradient(90deg, var(--neon-cyan), var(--neon-pink));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .stat-label {
            font-size: 1rem;
            color: #aaa;
        }
        
        /* Tech Stack */
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .tech-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 1rem;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            transition: all 0.3s ease;
        }
        
        .tech-item:hover {
            transform: translateY(-5px) scale(1.1);
            box-shadow: 0 0 15px var(--neon-green);
        }
        
        .tech-icon {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .tech-name {
            font-size: 0.8rem;
            text-align: center;
            color: #ccc;
        }
        
        /* Social Links */
        .social-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .social-link {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            color: #fff;
            background: rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .social-link::before {
            content: '';
            position: absolute;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, var(--neon-cyan), var(--neon-pink));
            opacity: 0;
            transition: opacity 0.3s ease;
            z-index: -1;
        }
        
        .social-link:hover {
            transform: translateY(-5px) rotate(10deg);
            color: #fff;
            box-shadow: 0 5px 15px rgba(0, 255, 255, 0.5);
        }
        
        .social-link:hover::before {
            opacity: 1;
        }
        
        /* Animations */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .float {
            animation: float 5s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(0, 255, 255, 0.7); }
            70% { box-shadow: 0 0 0 15px rgba(0, 255, 255, 0); }
            100% { box-shadow: 0 0 0 0 rgba(0, 255, 255, 0); }
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
        
        /* Matrix Rain Effect */
        .matrix-rain {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -2;
            opacity: 0.1;
            pointer-events: none;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .glitch {
                font-size: 2.5rem;
            }
            
            .typing-text {
                font-size: 1.2rem;
            }
            
            .stats-grid {
                grid-template-columns: 1fr;
            }
            
            .tech-grid {
                grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));
            }
            
            .social-links {
                flex-wrap: wrap;
            }
        }
    </style>
</head>
<body>
    <!-- Particles.js Background -->
    <div id="particles-js"></div>
    
    <!-- Matrix Rain Effect -->
    <canvas class="matrix-rain" id="matrixRain"></canvas>
    
    <div class="container">
        <!-- Header Section -->
        <header class="header">
            <div class="glitch-wrapper">
                <h1 class="glitch" data-text="🔥 Welcome to My World 🔥">🔥 Welcome to My World 🔥</h1>
            </div>
            
            <div class="typing-container">
                <p class="typing-text" id="typing"></p>
            </div>
        </header>
        
        <!-- About Me Section -->
        <section class="section">
            <h2 class="section-title"><i class="fas fa-user-astronaut"></i> About Me</h2>
            <p>🧑‍💻 Full-time <strong class="neon-text">Code Wizard</strong> with a passion for creating digital magic</p>
            <p>🤖 AI/ML Enthusiast | Backend Dev | Professional Bug Collector</p>
            <p>🎮 Competitive Gamer, Meme Connoisseur & Digital Nomad</p>
            <p>🥶 Writing spaghetti code but serving it like Michelin star cuisine</p>
            
            <div class="stats-grid">
                <div class="stat-card float">
                    <div class="stat-number" id="coffee-cups">0</div>
                    <div class="stat-label">Cups of Coffee</div>
                </div>
                <div class="stat-card float" style="animation-delay: 1s;">
                    <div class="stat-number" id="projects-completed">0</div>
                    <div class="stat-label">Projects Completed</div>
                </div>
                <div class="stat-card float" style="animation-delay: 2s;">
                    <div class="stat-number" id="bugs-created">0</div>
                    <div class="stat-label">Bugs Created</div>
                </div>
                <div class="stat-card float" style="animation-delay: 3s;">
                    <div class="stat-number" id="bugs-fixed">0</div>
                    <div class="stat-label">Bugs Fixed</div>
                </div>
            </div>
        </section>
        
        <!-- GitHub Stats Section -->
        <section class="section">
            <h2 class="section-title"><i class="fas fa-chart-line"></i> GitHub Stats</h2>
            
            <div class="stats-grid">
                <div class="stat-card pulse">
                    <div class="stat-number">128</div>
                    <div class="stat-label">Contributions</div>
                </div>
                <div class="stat-card pulse" style="animation-delay: 0.5s;">
                    <div class="stat-number">42</div>
                    <div class="stat-label">Repositories</div>
                </div>
                <div class="stat-card pulse" style="animation-delay: 1s;">
                    <div class="stat-number">24</div>
                    <div class="stat-label">Stars Earned</div>
                </div>
                <div class="stat-card pulse" style="animation-delay: 1.5s;">
                    <div class="stat-number">18</div>
                    <div class="stat-label">Followers</div>
                </div>
            </div>
            
            <div style="text-align: center; margin-top: 2rem;">
                <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=react-dark&bg_color=050510&hide_border=true&area=true" alt="Activity Graph" style="max-width: 100%; border-radius: 10px;" />
            </div>
            
            <div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin-top: 2rem;">
                <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight" alt="GitHub Stats" style="max-width: 100%; margin: 10px; border-radius: 10px;" />
                <img src="https://github-readme-streak-stats.herokuapp.com?user=YOUR_USERNAME&theme=tokyonight" alt="Streak Stats" style="max-width: 100%; margin: 10px; border-radius: 10px;" />
            </div>
        </section>
        
        <!-- Tech Stack Section -->
        <section class="section">
            <h2 class="section-title"><i class="fas fa-laptop-code"></i> Tech Stack</h2>
            
            <div class="tech-grid">
                <div class="tech-item">
                    <i class="fab fa-python tech-icon"></i>
                    <span class="tech-name">Python</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-js tech-icon"></i>
                    <span class="tech-name">JavaScript</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-react tech-icon"></i>
                    <span class="tech-name">React</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-node-js tech-icon"></i>
                    <span class="tech-name">Node.js</span>
                </div>
                <div class="tech-item">
                    <i class="fas fa-database tech-icon"></i>
                    <span class="tech-name">MongoDB</span>
                </div>
                <div class="tech-item">
                    <i class="fas fa-database tech-icon"></i>
                    <span class="tech-name">MySQL</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-docker tech-icon"></i>
                    <span class="tech-name">Docker</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-aws tech-icon"></i>
                    <span class="tech-name">AWS</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-git-alt tech-icon"></i>
                    <span class="tech-name">Git</span>
                </div>
                <div class="tech-item">
                    <i class="fab fa-linux tech-icon"></i>
                    <span class="tech-name">Linux</span>
                </div>
            </div>
        </section>
        
        <!-- Fun Section -->
        <section class="section">
            <h2 class="section-title"><i class="fas fa-gamepad"></i> Fun Zone</h2>
            
            <div style="text-align: center; margin: 2rem 0;">
                <blockquote style="font-style: italic; border-left: 3px solid var(--neon-cyan); padding-left: 1rem;">
                    "I commit my life mistakes with <code style="background: rgba(0,0,0,0.3); padding: 2px 5px; border-radius: 3px;">git push -f</code>"
                </blockquote>
            </div>
            
            <div style="display: flex; justify-content: space-around; flex-wrap: wrap;">
                <img src="https://media.giphy.com/media/3oKIPwoeGErMmaI43C/giphy.gif" alt="Coding Meme" style="max-width: 300px; margin: 10px; border-radius: 10px; box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);" />
                <img src="https://media.giphy.com/media/26xBP3lPAFz9FqF0w/giphy.gif" alt="Debugging Meme" style="max-width: 300px; margin: 10px; border-radius: 10px; box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);" />
            </div>
        </section>
        
        <!-- Connect Section -->
        <section class="section">
            <h2 class="section-title"><i class="fas fa-handshake"></i> Let's Connect</h2>
            
            <div class="social-links">
                <a href="https://twitter.com/YOUR_HANDLE" class="social-link">
                    <i class="fab fa-twitter"></i>
                </a>
                <a href="https://linkedin.com/in/YOUR_HANDLE" class="social-link">
                    <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://discord.gg/YOUR_INVITE" class="social-link">
                    <i class="fab fa-discord"></i>
                </a>
                <a href="mailto:your@email.com" class="social-link">
                    <i class="fas fa-envelope"></i>
                </a>
                <a href="https://github.com/YOUR_USERNAME" class="social-link">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </section>
        
        <footer style="text-align: center; margin: 3rem 0; color: #888;">
            <p>🔥 Thanks for scrolling all the way down 🔥</p>
            <p>Now go check out my repos 😎</p>
        </footer>
    </div>

    <script>
        // Particles.js Configuration
        particlesJS('particles-js', {
            particles: {
                number: { value: 80, density: { enable: true, value_area: 800 } },
                color: { value: "#00ffff" },
                shape: { type: "circle" },
                opacity: { value: 0.5, random: true },
                size: { value: 3, random: true },
                line_linked: {
                    enable: true,
                    distance: 150,
                    color: "#00ffff",
                    opacity: 0.4,
                    width: 1
                },
                move: {
                    enable: true,
                    speed: 2,
                    direction: "none",
                    random: true,
                    straight: false,
                    out_mode: "out",
                    bounce: false
                }
            },
            interactivity: {
                detect_on: "canvas",
                events: {
                    onhover: { enable: true, mode: "repulse" },
                    onclick: { enable: true, mode: "push" },
                    resize: true
                }
            },
            retina_detect: true
        });
        
        // Matrix Rain Effect
        const matrixCanvas = document.getElementById('matrixRain');
        const ctx = matrixCanvas.getContext('2d');
        
        matrixCanvas.width = window.innerWidth;
        matrixCanvas.height = window.innerHeight;
        
        const letters = 'アァカサタナハマヤャラワガザダバパイィキシチニヒミリヰギジヂビピウゥクスツヌフムユュルグズブヅプエェケセテネヘメレヱゲゼデベペオォコソトノホモヨョロヲゴゾドボポヴッン0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ';
        const fontSize = 14;
        const columns = matrixCanvas.width / fontSize;
        
        const drops = [];
        for(let i = 0; i < columns; i++) {
            drops[i] = 1;
        }
        
        function drawMatrix() {
            ctx.fillStyle = 'rgba(5, 5, 16, 0.1)';
            ctx.fillRect(0, 0, matrixCanvas.width, matrixCanvas.height);
            
            ctx.fillStyle = '#0f0';
            ctx.font = `${fontSize}px monospace`;
            
            for(let i = 0; i < drops.length; i++) {
                const text = letters[Math.floor(Math.random() * letters.length)];
                ctx.fillText(text, i * fontSize, drops[i] * fontSize);
                
                if(drops[i] * fontSize > matrixCanvas.height && Math.random() > 0.975) {
                    drops[i] = 0;
                }
                
                drops[i]++;
            }
        }
        
        setInterval(drawMatrix, 33);
        
        // Typing Effect
        const typingText = document.getElementById('typing');
        const phrases = [
            "👋 Hello, World!",
            "💻 I am an Open Source Addict",
            "🚀 Building Cool Projects",
            "😎 Making Code Look Sexy",
            "🌌 Exploring the Digital Universe",
            "⚡ Pushing the Boundaries of Tech"
        ];
        let phraseIndex = 0;
        let letterIndex = 0;
        let currentPhrase = '';
        let isDeleting = false;
        let isEnd = false;
        
        function type() {
            isEnd = false;
            
            if (!isDeleting && letterIndex <= phrases[phraseIndex].length) {
                currentPhrase = phrases[phraseIndex].substr(0, letterIndex);
                letterIndex += 1;
                typingText.innerHTML = currentPhrase;
            }
            
            if (isDeleting && letterIndex >= 0) {
                currentPhrase = phrases[phraseIndex].substr(0, letterIndex);
                letterIndex -= 1;
                typingText.innerHTML = currentPhrase;
            }
            
            if (letterIndex === phrases[phraseIndex].length) {
                isEnd = true;
                isDeleting = true;
            }
            
            if (isDeleting && letterIndex === 0) {
                isDeleting = false;
                phraseIndex = (phraseIndex + 1) % phrases.length;
            }
            
            const speedUp = Math.random() * (80 - 50) + 50;
            const normalSpeed = Math.random() * (300 - 200) + 200;
            const time = isEnd ? 2000 : isDeleting ? speedUp : normalSpeed;
            
            setTimeout(type, time);
        }
        
        // Start typing effect
        setTimeout(type, 1000);
        
        // Counter Animation
        function animateCounter(elementId, finalValue, duration) {
            let startTime = null;
            const element = document.getElementById(elementId);
            
            function updateCounter(timestamp) {
                if (!startTime) startTime = timestamp;
                const progress = timestamp - startTime;
                const progressPercentage = Math.min(progress / duration, 1);
                
                const value = Math.floor(progressPercentage * finalValue);
                element.textContent = value;
                
                if (progress < duration) {
                    window.requestAnimationFrame(updateCounter);
                } else {
                    element.textContent = finalValue;
                }
            }
            
            window.requestAnimationFrame(updateCounter);
        }
        
        // Start counter animations when in viewport
        function startCounters() {
            animateCounter('coffee-cups', 1274, 2000);
            animateCounter('projects-completed', 42, 2500);
            animateCounter('bugs-created', 999, 3000);
            animateCounter('bugs-fixed', 427, 3500);
        }
        
        // Wait for page to load before starting counters
        window.addEventListener('load', startCounters);
        
        // Update canvas size on window resize
        window.addEventListener('resize', function() {
            matrixCanvas.width = window.innerWidth;
            matrixCanvas.height = window.innerHeight;
        });
    </script>
</body>
</html>
