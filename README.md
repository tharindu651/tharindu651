<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Tharindu Lakmal · AI Full Stack Dev</title>
    <!-- Google Fonts & Smooth Scrolling -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: #0a0c10;
            font-family: 'Inter', sans-serif;
            color: #eef5ff;
            line-height: 1.5;
            scroll-behavior: smooth;
        }
        .container {
            max-width: 1280px;
            margin: 0 auto;
            padding: 1.5rem 2rem;
        }
        /* animated gradient borders */
        .glow-card {
            background: rgba(15, 20, 30, 0.65);
            backdrop-filter: blur(2px);
            border-radius: 2rem;
            border: 1px solid rgba(0, 255, 255, 0.2);
            transition: all 0.25s ease;
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }
        .glow-card:hover {
            border-color: #0ff;
            box-shadow: 0 0 18px rgba(0, 255, 255, 0.2);
        }
        .section-title {
            font-size: 2.2rem;
            font-weight: 700;
            background: linear-gradient(135deg, #e0f2fe, #7dd3fc, #2dd4bf);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            display: inline-block;
            margin-bottom: 1.5rem;
            letter-spacing: -0.3px;
            border-left: 5px solid #0ff;
            padding-left: 1rem;
        }
        .badge-group {
            display: flex;
            flex-wrap: wrap;
            gap: 0.6rem;
            justify-content: center;
            margin: 1rem 0;
        }
        .skill-icon {
            background: #11161f;
            border-radius: 20px;
            padding: 8px 16px;
            font-size: 0.9rem;
            font-weight: 500;
            transition: all 0.2s;
            border: 1px solid #2a3342;
        }
        .skill-icon:hover {
            transform: translateY(-3px);
            border-color: #0ff;
            background: #0a1118;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.8rem;
            margin: 2rem 0;
        }
        .project-card {
            background: #0f131c;
            border-radius: 1.5rem;
            padding: 1.5rem;
            transition: all 0.3s cubic-bezier(0.2, 0.9, 0.4, 1.1);
            border: 1px solid #1e293b;
        }
        .project-card:hover {
            transform: translateY(-8px);
            border-color: #0ff;
            box-shadow: 0 20px 30px -12px rgba(0,255,255,0.1);
        }
        .tech-badge {
            background: #0a0f17;
            padding: 0.25rem 0.75rem;
            border-radius: 30px;
            font-size: 0.7rem;
            font-weight: 500;
            color: #a5f3fc;
            border: 1px solid #2d3a4e;
        }
        .stats-wrapper {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem;
            margin: 2rem 0;
        }
        .stat-img {
            border-radius: 16px;
            background: #0f131c;
            transition: transform 0.2s;
        }
        .stat-img:hover {
            transform: scale(1.02);
        }
        .typing-animation {
            font-size: 1.3rem;
            font-weight: 500;
            background: linear-gradient(120deg, #b0f3ff, #6ee7ff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        hr {
            border: 0;
            height: 2px;
            background: linear-gradient(90deg, transparent, #0ff, #f0f, transparent);
            margin: 2rem 0;
        }
        footer {
            text-align: center;
            padding: 2rem 0 1rem;
            font-size: 0.85rem;
            color: #8ca3b9;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            100% { transform: translateY(-5px); }
        }
        .floating {
            animation: float 3s ease-in-out infinite;
        }
        @media (max-width: 680px) {
            .container { padding: 1rem; }
            .section-title { font-size: 1.8rem; }
        }
        .gradient-text {
            background: linear-gradient(145deg, #ffffff, #0ff, #a855f7);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }
    </style>
</head>
<body>

<div class="container">

    <!-- ===================== ANIMATED HERO (capsule style but fully custom) ================= -->
    <div style="position: relative; text-align: center; margin-bottom: 1rem;">
        <div style="background: linear-gradient(120deg, #021a2c, #000000, #01131f); border-radius: 60px; padding: 2rem 1rem 2rem; margin-bottom: 1rem; border-bottom: 3px solid cyan; box-shadow: 0 10px 25px -5px rgba(0,255,255,0.2);">
            <h1 style="font-size: 3.2rem; font-weight: 800; letter-spacing: -1px;">
                <span class="gradient-text">THARINDU LAKMAL</span>
            </h1>
            <div class="typing-animation" style="font-size: 1.3rem; margin: 0.8rem 0;">
                ⚡ Full Stack • AI/ML • Computer Vision • Deep Learning • Sri Lanka 🇱🇰
            </div>
            <div class="badge-group">
                <span class="skill-icon">🎓 GPA 3.2/4.0</span>
                <span class="skill-icon">🏆 Final Year CS</span>
                <span class="skill-icon">🚀 20+ Projects</span>
                <span class="skill-icon">🤖 TensorFlow Certified</span>
            </div>
            <!-- animated social row -->
            <div class="badge-group">
                <a href="https://linkedin.com/in/tharindu-lakmal" target="_blank" style="text-decoration: none;"><img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="32"/></a>
                <a href="mailto:tharindulakmal651@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&color=00FFFF" height="32"/></a>
                <a href="https://wa.me/940788069259" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" height="32"/></a>
                <a href="https://github.com/tharindu651" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" height="32"/></a>
            </div>
            <div style="margin-top: 1rem;">
                <img src="https://komarev.com/ghpvc/?username=tharindu651&label=Profile%20views&color=00FFFF&style=flat-square" alt="views"/>
                <img src="https://img.shields.io/github/followers/tharindu651?label=Followers&style=flat-square&color=00FFFF"/>
                <img src="https://img.shields.io/github/stars/tharindu651?label=Stars&style=flat-square&color=ffd700"/>
            </div>
        </div>
    </div>

    <!-- Typing SVG (animated) -->
    <div align="center" style="margin: 1rem 0 2rem;">
        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=800&color=00FFFF&center=true&vCenter=true&width=860&lines=💻+Full+Stack+Developer+%7C+MERN+Stack;🤖+AI+%7C+ML+Engineer+%7C+TensorFlow+%7C+PyTorch;👁️+Computer+Vision+%7C+OpenCV+%7C+CNN;☁️+DevOps+Engineer+%7C+Docker+%7C+Git;🎨+UI%2FUX+Designer+%7C+Figma+%7C+Tailwind;🏆+Final+Year+%7C+Building+Intelligent+Systems" alt="Typing Animation"/>
    </div>

    <!-- ================= ABOUT ME SECTION ================= -->
    <div class="glow-card" style="padding: 1.8rem; margin: 2rem 0;">
        <h2 class="section-title">🎓 About Me</h2>
        <div style="display: flex; flex-wrap: wrap; gap: 1rem; align-items: center; justify-content: space-between;">
            <div style="flex: 2; min-width: 200px;">
                <p style="font-size: 1.05rem;">I'm <strong>Tharindu Lakmal</strong> — final year Computer Science undergraduate at <strong>Eastern University Sri Lanka (Trincomalee Campus)</strong> with a passion for building intelligent, scalable systems. I blend <strong>Full Stack craft (MERN)</strong> with <strong>AI/Computer Vision</strong> to solve real-world problems.</p>
                <br/>
                <p>💡 Currently deep-diving into <strong>medical image segmentation, LSTM forecasting & MERN AI apps</strong>.<br/>
                📬 <strong>Email:</strong> tharindulakmal651@gmail.com &nbsp;| 📍 Jayanthipura, Sri Lanka 🇱🇰</p>
                <div class="badge-group" style="justify-content: flex-start; margin-top: 1rem;">
                    <span class="skill-icon">🤝 Team Leadership</span>
                    <span class="skill-icon">⚡ Problem Solver</span>
                    <span class="skill-icon">🎯 Agile Mindset</span>
                </div>
            </div>
            <div style="flex: 1; text-align: center;">
                <div style="background: radial-gradient(circle, #0ff1, transparent); border-radius: 30px; padding: 0.5rem;">
                    <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Penguin.png" width="90" style="filter: drop-shadow(0 0 6px cyan);"/>
                </div>
            </div>
        </div>
    </div>

    <!-- ================= GITHUB STATS (animated hover) ================= -->
    <h2 class="section-title">📊 GitHub Pulse & Achievements</h2>
    <div class="stats-wrapper">
        <img class="stat-img" height="180" src="https://github-readme-stats-eight-theta.vercel.app/api?username=tharindu651&show_icons=true&theme=dark&border_radius=12&count_private=true&bg_color=0d1117&title_color=0ff&icon_color=0ff"/>
        <img class="stat-img" height="180" src="https://streak-stats.demolab.com/?user=tharindu651&theme=dark&hide_border=true&ring=00FFFF&fire=ff6b6b&currStreakLabel=00FFFF&background=0d1117"/>
    </div>
    <div align="center">
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=tharindu651&bg_color=0d1117&color=00FFFF&line=00FFFF&point=ffffff&area=true&hide_border=true" width="98%" style="border-radius: 16px; margin-bottom: 1rem;"/>
    </div>
    <div align="center">
        <img src="https://trophy.ryglcloud.net/?username=tharindu651&theme=dark&no-frame=true&no-bg=true&margin-w=4&column=6" width="98%"/>
    </div>

    <!-- ================= FEATURED PROJECTS ================= -->
    <h2 class="section-title">🌟 Featured Projects</h2>
    <div class="project-grid">
        <div class="project-card">
            <h3 style="font-size: 1.6rem; margin-bottom: 0.3rem;">🏨 Hotel Management System</h3>
            <p>Full-stack MERN — real-time room booking, restaurant ordering, automated email receipts (NodeMailer).</p>
            <div class="badge-group" style="margin: 1rem 0 0.5rem; justify-content: flex-start;">
                <span class="tech-badge">React</span><span class="tech-badge">Node.js</span><span class="tech-badge">MongoDB</span><span class="tech-badge">Express</span>
            </div>
            <a href="https://github.com/tharindu651" style="color:#0ff;">🔗 View Repo →</a>
        </div>
        <div class="project-card">
            <h3 style="font-size: 1.6rem;">🌾 Smart Agriculture AI</h3>
            <p>Crop disease detection via CNN + OpenCV, AI-powered pesticide recommendation, and yield predictions.</p>
            <div class="badge-group" style="margin: 1rem 0 0.5rem; justify-content: flex-start;">
                <span class="tech-badge">Python</span><span class="tech-badge">TensorFlow</span><span class="tech-badge">OpenCV</span><span class="tech-badge">Flask</span>
            </div>
            <a href="https://github.com/tharindu651" style="color:#0ff;">🔗 Explore →</a>
        </div>
        <div class="project-card">
            <h3 style="font-size: 1.6rem;">🧠 Brain Tumor Segmentation</h3>
            <p>MRI image segmentation using K-Means + PCA. Automates tumor area detection and visualization.</p>
            <div class="badge-group" style="margin: 1rem 0 0.5rem;">
                <span class="tech-badge">Python</span><span class="tech-badge">OpenCV</span><span class="tech-badge">Scikit-learn</span>
            </div>
            <a href="https://github.com/tharindu651" style="color:#0ff;">📁 GitHub →</a>
        </div>
    </div>

    <!-- ================= ALL PROJECTS (expanded categories) ================= -->
    <h2 class="section-title">🚀 All Projects by Domain</h2>
    <details open style="margin: 1rem 0; background: #0f131c; border-radius: 24px; padding: 0 1rem 1rem;">
        <summary style="font-size: 1.4rem; font-weight: 700; cursor: pointer; padding: 1rem 0; color: #2dd4bf;">🌐 Full Stack MERN & Web</summary>
        <div class="project-grid" style="grid-template-columns: repeat(auto-fill, minmax(270px,1fr));">
            <div class="project-card">🏨 Hotel Booking & Meal System · MERN + NodeMailer</div>
            <div class="project-card">🌾 Smart Agriculture Machine Booking · React + MySQL</div>
            <div class="project-card">🛒 MERN E‑Commerce (JWT, cart, orders)</div>
            <div class="project-card">✅ Task Manager · MongoDB CRUD · RESTful</div>
        </div>
    </details>
    <details style="margin: 1rem 0; background: #0f131c; border-radius: 24px; padding: 0 1rem 1rem;">
        <summary style="font-size: 1.4rem; font-weight: 700; cursor: pointer; padding: 1rem 0; color: #2dd4bf;">🤖 Machine & Deep Learning</summary>
        <div class="project-grid">
            <div class="project-card">🦠 COVID‑19 Outbreak Prediction · Linear Regression</div>
            <div class="project-card">🚗 Autonomous Navigation CNN (Behavioral Cloning)</div>
            <div class="project-card">❤️ Heart Disease Risk Predictor · Keras + React + Flask</div>
            <div class="project-card">📈 Stock Market LSTM Forecasting · TensorFlow</div>
        </div>
    </details>
    <details style="margin: 1rem 0; background: #0f131c; border-radius: 24px; padding: 0 1rem 1rem;">
        <summary style="font-size: 1.4rem; font-weight: 700; cursor: pointer; padding: 1rem 0; color: #2dd4bf;">👁️ Computer Vision & Edge AI</summary>
        <div class="project-grid">
            <div class="project-card">🛣️ Lane Detection & Distance Estimation · OpenCV · Hough Transform</div>
            <div class="project-card">🚗 Vehicle Counter (Haar Cascade) · Real‑time traffic</div>
            <div class="project-card">😶 Face Recognition · SVM + PCA</div>
        </div>
    </details>

    <!-- ================= LANGUAGES & TOOLS (animated floating icons) ================= -->
    <h2 class="section-title">🛠️ Tech Arsenal</h2>
    <div style="background: #0b1018; border-radius: 2rem; padding: 1.2rem; margin: 1.2rem 0;">
        <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 1.2rem;">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="45" title="JS"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="45"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="45"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="45"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" width="45"/>
            <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" width="45"/>
            <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" width="45"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="45"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="45"/>
            <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="45"/>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" width="45" style="filter: invert(1);"/>
        </div>
        <div class="badge-group" style="margin-top: 1rem;">
            <span class="skill-icon">🐳 Docker/K8s</span><span class="skill-icon">☁️ AWS/GCP</span><span class="skill-icon">🎨 TailwindCSS</span><span class="skill-icon">📊 Pandas/Numpy</span><span class="skill-icon">⚡ FastAPI</span>
        </div>
    </div>

    <!-- ================= PAC-MAN Contribution Graph (animated snake/pacman) ================= -->
    <h2 class="section-title">🕹️ Pac‑Man eats my contributions</h2>
    <div style="background: #0a0c10; border-radius: 32px; padding: 0.5rem; text-align: center;">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/abozanona/abozanona/output/pacman-contribution-graph-dark.svg">
            <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/abozanona/abozanona/output/pacman-contribution-graph-dark.svg" width="100%" style="border-radius: 24px;">
        </picture>
        <p style="font-size: 0.8rem; margin-top: 8px;">✨ contributions get devoured by Pac‑Man — updated every 12h ✨</p>
    </div>

    <!-- ================= SOFT SKILLS + QUOTE ================= -->
    <h2 class="section-title">🧠 Beyond Code</h2>
    <div class="glow-card" style="padding: 1.5rem; text-align: center;">
        <div class="badge-group" style="justify-content: center;">
            <img src="https://img.shields.io/badge/Teamwork-00FFFF?style=for-the-badge"/>
            <img src="https://img.shields.io/badge/Leadership-FF6B6B?style=for-the-badge"/>
            <img src="https://img.shields.io/badge/Time%20Management-FFD700?style=for-the-badge"/>
            <img src="https://img.shields.io/badge/Critical%20Thinking-A855F7?style=for-the-badge"/>
            <img src="https://img.shields.io/badge/Effective%20Communication-22C55E?style=for-the-badge"/>
        </div>
        <div style="margin: 1.5rem 0;">
            <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" width="90%"/>
        </div>
        <p style="font-weight: 500;">💬 “Building AI solutions that matter — one commit at a time.”</p>
    </div>

    <!-- ================= CONNECT & SUPPORT ================= -->
    <hr/>
    <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 1rem;">
        <div>
            <h3 style="color:#0ff;">🔗 Let’s connect & collaborate</h3>
            <div class="badge-group">
                <a href="https://linkedin.com/in/tharindu-lakmal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
                <a href="https://github.com/tharindu651"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
                <a href="mailto:tharindulakmal651@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
            </div>
        </div>
        <div>
            <a href="https://www.buymeacoffee.com/tharindu651" target="_blank">
                <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="160" alt="Buy Me A Coffee"/>
            </a>
        </div>
    </div>

    <footer>
        ⭐ If you find my work helpful, star repositories & let's build the future together!<br/>
        <span style="font-size: 0.7rem;">Made with 🧠 by Tharindu Lakmal — AI Full Stack | Final Year CS @ Eastern University Sri Lanka</span><br/>
        <span>🚀 <strong>Profile views:</strong> <img src="https://komarev.com/ghpvc/?username=tharindu651&color=cyan&style=flat-square"/></span>
    </footer>
</div>

<!-- smooth floating effect on some icons -->
<script>
    // simple dynamic style for floating icons (optional)
    const icons = document.querySelectorAll('img[width="45"]');
    icons.forEach((icon, idx) => {
        icon.style.transition = 'transform 0.2s';
        icon.addEventListener('mouseenter', () => icon.style.transform = 'translateY(-5px)');
        icon.addEventListener('mouseleave', () => icon.style.transform = 'translateY(0)');
    });
</script>
</body>
</html>
