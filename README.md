<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Syedain Iqbal Shigri - Portfolio</title>
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    
    <style>
        /* --- RESET & VARIABLES --- */
        :root {
            --bg-dark: #0f172a;
            --bg-card: rgba(30, 41, 59, 0.7);
            --primary: #38bdf8;
            --secondary: #818cf8;
            --accent: #2dd4bf;
            --text-main: #f1f5f9;
            --text-muted: #94a3b8;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background-color: var(--bg-dark);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow-x: hidden;
        }

        /* --- CONTAINER --- */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            animation: fadeIn 1.5s ease-out;
        }

        /* --- HEADER SECTION --- */
        .header {
            text-align: center;
            margin-bottom: 60px;
            position: relative;
        }

        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid var(--primary);
            box-shadow: 0 0 20px rgba(56, 189, 248, 0.4);
            margin-bottom: 20px;
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .name {
            font-size: 3rem;
            font-weight: 800;
            background: linear-gradient(to right, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }

        .typing-container {
            font-family: 'JetBrains Mono', monospace;
            color: var(--accent);
            font-size: 1.2rem;
            height: 30px;
            display: inline-block;
        }

        .cursor {
            display: inline-block;
            width: 2px;
            height: 1.2rem;
            background-color: var(--accent);
            animation: blink 1s step-end infinite;
        }

        @keyframes blink {
            50% { opacity: 0; }
        }

        /* --- LAYOUT GRIDS --- */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        /* --- CARDS --- */
        .card {
            background: var(--bg-card);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 25px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            border-color: var(--primary);
        }

        h2 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--primary);
        }

        h3 {
            font-size: 1rem;
            margin-bottom: 15px;
            color: var(--secondary);
        }

        ul {
            list-style: none;
            padding-left: 10px;
        }

        li {
            margin-bottom: 8px;
            display: flex;
            align-items: center;
        }

        li::before {
            content: '▹';
            color: var(--accent);
            margin-right: 10px;
            font-size: 1.2rem;
        }

        /* --- SKILL BADGES --- */
        .skill-tag {
            display: inline-block;
            background: rgba(56, 189, 248, 0.1);
            color: var(--primary);
            padding: 5px 15px;
            border-radius: 20px;
            margin: 5px;
            border: 1px solid rgba(56, 189, 248, 0.3);
            font-size: 0.9rem;
            font-weight: 600;
        }

        /* --- PROJECT CARD --- */
        .project-card {
            border-left: 4px solid var(--accent);
        }

        /* --- STATS --- */
        .stats {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-bottom: 40px;
        }

        .stat-box {
            background: linear-gradient(145deg, #1e293b, #0f172a);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            min-width: 200px;
            border: 1px solid #334155;
        }

        .stat-num {
            font-size: 2rem;
            font-weight: 800;
            color: var(--text-main);
        }

        /* --- FOOTER --- */
        .footer {
            text-align: center;
            margin-top: 60px;
            padding-top: 20px;
            border-top: 1px solid #334155;
        }

        .social-link {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.05);
            margin: 0 10px;
            transition: 0.3s;
            color: var(--text-main);
            text-decoration: none;
        }

        .social-link:hover {
            background: var(--primary);
            color: white;
            transform: scale(1.1);
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            .grid { grid-template-columns: 1fr; }
            .name { font-size: 2rem; }
            .stats { flex-direction: column; gap: 10px; }
        }
    </style>
</head>
<body>

    <div class="container">
        
        <!-- HEADER -->
        <div class="header">
            <img src="https://avatars.githubusercontent.com/u/Syedain-Iqbal-Shigri?v=4" alt="Profile" class="avatar">
            <div class="name">Syedain Iqbal Shigri</div>
            
            <!-- TYPING ANIMATION -->
            <div class="typing-container">
                <span id="typewriter"></span><span class="cursor">&nbsp;</span>
            </div>
        </div>

        <!-- SKILLS SECTION -->
        <div class="grid">
            <div class="card">
                <h2>Frontend</h2>
                <div>
                    <span class="skill-tag">React</span>
                    <span class="skill-tag">Tailwind CSS</span>
                    <span class="skill-tag">Bootstrap</span>
                    <span class="skill-tag">HTML5</span>
                    <span class="skill-tag">CSS3</span>
                </div>
            </div>

            <div class="card">
                <h2>Backend</h2>
                <div>
                    <span class="skill-tag">Node.js</span>
                    <span class="skill-tag">Express.js</span>
                    <span class="skill-tag">MongoDB</span>
                    <span class="skill-tag">MySQL</span>
                    <span class="skill-tag">PHP</span>
                </div>
            </div>

            <div class="card">
                <h2>Tools</h2>
                <div>
                    <span class="skill-tag">Git & GitHub</span>
                    <span class="skill-tag">WordPress</span>
                    <span class="skill-tag">VS Code</span>
                    <span class="skill-tag">Postman</span>
                </div>
            </div>
        </div>

        <!-- PROJECT SECTION -->
        <div class="card project-card" style="margin-bottom: 40px;">
            <h2>🚀 Current Project: Hotel Management System</h2>
            <p>A comprehensive full-stack MERN application designed for scalability and user experience.</p>
            <ul style="margin-top: 15px;">
                <li>User Friendly Interface</li>
                <li>Speed Optimization</li>
                <li>Real-time API Communication</li>
                <li>Scalable MongoDB Architecture</li>
            </ul>
        </div>

        <!-- STATS PLACEHOLDER -->
        <div class="stats">
            <div class="stat-box">
                <div class="stat-num">120+</div>
                <div style="color: var(--text-muted);">Commits</div>
            </div>
            <div class="stat-box">
                <div class="stat-num">5+</div>
                <div style="color: var(--text-muted);">Projects</div>
            </div>
            <div class="stat-box">
                <div class="stat-num">20</div>
                <div style="color: var(--text-muted);">Repositories</div>
            </div>
        </div>

        <!-- FOOTER -->
        <div class="footer">
            <h3 style="margin-bottom: 20px;">Connect With Me</h3>
            <a href="https://github.com/Syedain-Iqbal-Shigri" class="social-link">GitHub</a>
            <a href="mailto:sishigree@gmail.com" class="social-link">Email</a>
            <a href="#" class="social-link">LinkedIn</a>
        </div>

    </div>

    <!-- SCRIPT FOR TYPING EFFECT -->
    <script>
        const text = "Full Stack Web Developer | MERN Stack | AI Enthusiast";
        const typeWriterElement = document.getElementById('typewriter');
        let i = 0;

        function typeWriter() {
            if (i < text.length) {
                typeWriterElement.innerHTML += text.charAt(i);
                i++;
                setTimeout(typeWriter, 100);
            } else {
                setTimeout(eraseText, 2000); // Wait before erasing
            }
        }

        function eraseText() {
            if (i > 0) {
                typeWriterElement.innerHTML = text.substring(0, i-1);
                i--;
                setTimeout(eraseText, 50);
            } else {
                setTimeout(typeWriter, 500); // Start over
            }
        }

        // Start animation
        document.addEventListener('DOMContentLoaded', typeWriter);
    </script>
</body>
</html>
