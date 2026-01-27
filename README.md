<!-- 
  NEXT LEVEL GITHUB PROFILE README
  Theme: Dark Glassmorphism & Neon
  Author: Syedain Iqbal Shigri
-->

<!-- 1. INTERNAL CSS FOR STYLING (No external files needed) -->
<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Poppins:wght@300;400;600;800&display=swap');

  body {
    font-family: 'Poppins', sans-serif;
    background-color: #0f172a;
    color: #e2e8f0;
    margin: 0;
    padding: 0;
  }

  /* Layout Container */
  .container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 40px 20px;
  }

  /* Header Section */
  .header {
    text-align: center;
    margin-bottom: 60px;
    position: relative;
  }

  .profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid #38bdf8;
    box-shadow: 0 0 20px rgba(56, 189, 248, 0.5);
    margin-bottom: 20px;
    animation: float 6s ease-in-out infinite;
  }

  @keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
    100% { transform: translateY(0px); }
  }

  .name {
    font-size: 2.5rem;
    font-weight: 800;
    margin: 0;
    background: linear-gradient(to right, #38bdf8, #818cf8);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  .role {
    font-family: 'JetBrains Mono', monospace;
    color: #94a3b8;
    font-size: 1.1rem;
    margin-top: 10px;
  }

  /* Grid Layouts */
  .grid-2 {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    margin-bottom: 40px;
  }

  /* Glassmorphism Cards */
  .card {
    background: rgba(30, 41, 59, 0.7);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 16px;
    padding: 30px;
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
    border-color: #38bdf8;
  }

  .section-title {
    font-size: 1.5rem;
    margin-bottom: 20px;
    color: #f8fafc;
    border-bottom: 2px solid #334155;
    padding-bottom: 10px;
    display: inline-block;
  }

  /* Tech Stack Badges */
  .tech-badge {
    display: inline-flex;
    align-items: center;
    background: #1e293b;
    padding: 8px 16px;
    border-radius: 20px;
    margin: 5px;
    font-size: 0.9rem;
    font-weight: 600;
    border: 1px solid #334155;
    transition: all 0.2s;
  }
  
  .tech-badge:hover {
    background: #38bdf8;
    color: #0f172a;
    border-color: #38bdf8;
  }

  .tech-icon { margin-right: 8px; }

  /* Project Card Specifics */
  .project-card {
    background: linear-gradient(145deg, #1e293b, #0f172a);
    border-left: 5px solid #38bdf8;
  }

  .project-link {
    color: #38bdf8;
    text-decoration: none;
    font-weight: bold;
  }
  .project-link:hover { text-decoration: underline; }

  /* Stats & Graphs */
  .stats-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 40px;
  }

  /* Footer */
  .footer {
    text-align: center;
    margin-top: 60px;
    padding-top: 20px;
    border-top: 1px solid #334155;
  }

  .social-link {
    text-decoration: none;
    color: #94a3b8;
    margin: 0 10px;
    font-size: 1.5rem;
    transition: color 0.3s;
  }
  .social-link:hover { color: #38bdf8; }

  /* Responsive */
  @media (max-width: 768px) {
    .name { font-size: 2rem; }
    .grid-2 { grid-template-columns: 1fr; }
  }
</style>

<div class="container">

  <!-- HEADER -->
  <div class="header">
    <!-- Using your GitHub Avatar directly -->
    <img src="https://avatars.githubusercontent.com/u/Syedain-Iqbal-Shigri?v=4" alt="Syedain Iqbal Shigri" class="profile-img" />
    
    <h1 class="name">Syedain Iqbal Shigri</h1>
    <p class="role">Full Stack Web Developer | MERN Stack | AI & NLP Enthusiast</p>
    
    <!-- Typing Animation -->
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=20&duration=4000&color=38bdf8&center=true&vCenter=true&width=600&lines=Building+Digital+Experiences;Transforming+Ideas+into+Code;Hotel+Management+System+Creator" alt="Typing" style="margin-top: 15px;" />
  </div>

  <!-- GITHUB STATS (2x2 Grid) -->
  <div class="stats-container">
    <!-- I corrected the username spelling here -->
    <img src="https://github-readme-stats.vercel.app/api?username=Syedain-Iqbal-Shigri&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1e293b&title_color=38bdf8&icon_color=38bdf8&text_color=e2e8f0" width="400" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Syedain-Iqbal-Shigri&layout=compact&theme=tokyonight&hide_border=true&bg_color=1e293b&title_color=38bdf8&text_color=e2e8f0" width="350" />
  </div>

  <!-- CURRENT PROJECT HIGHLIGHT -->
  <div class="grid-2">
    <div class="card project-card" style="grid-column: span 2;">
      <h2 class="section-title">🚀 Current Masterpiece: Hotel Management System</h2>
      <p>A full-featured, scalable MERN application designed to streamline hospitality operations.</p>
      
      <h3 style="color:#94a3b8; margin-top:20px;">Tech Stack Used:</h3>
      <div style="margin-top: 10px;">
        <span class="tech-badge">React.js</span>
        <span class="tech-badge">Node.js</span>
        <span class="tech-badge">Express.js</span>
        <span class="tech-badge">MongoDB</span>
        <span class="tech-badge">Tailwind CSS</span>
      </div>

      <ul style="margin-top: 20px; line-height: 1.6; color: #cbd5e1;">
        <li>✅ <strong>User Friendly Interface:</strong> Intuitive design for seamless booking.</li>
        <li>✅ <strong>Speed Optimization:</strong> High-performance API architecture.</li>
        <li>✅ <strong>Real-time Communication:</strong> Socket integration for live updates.</li>
        <li>✅ <strong>Secure Database:</strong> Scalable MongoDB structure for data integrity.</li>
      </ul>
    </div>
  </div>

  <!-- SKILLS GRID -->
  <h2 class="section-title">🛠️ Technical Arsenal</h2>
  <div class="grid-2">
    
    <!-- Frontend -->
    <div class="card">
      <h3 style="color: #38bdf8; margin-bottom: 15px;">Frontend Development</h3>
      <div>
        <span class="tech-badge"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="15" class="tech-icon" /> React</span>
        <span class="tech-badge"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="15" class="tech-icon" /> JavaScript</span>
        <span class="tech-badge">HTML5</span>
        <span class="tech-badge">CSS3</span>
        <span class="tech-badge">Tailwind</span>
        <span class="tech-badge">Bootstrap</span>
      </div>
    </div>

    <!-- Backend -->
    <div class="card">
      <h3 style="color: #f472b6; margin-bottom: 15px;">Backend & Database</h3>
      <div>
        <span class="tech-badge"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="15" class="tech-icon" /> Node.js</span>
        <span class="tech-badge"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="15" class="tech-icon" /> Express</span>
        <span class="tech-badge"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="15" class="tech-icon" /> MongoDB</span>
        <span class="tech-badge"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="15" class="tech-icon" /> MySQL</span>
        <span class="tech-badge"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" width="15" class="tech-icon" /> PHP</span>
      </div>
    </div>

    <!-- Tools -->
    <div class="card">
      <h3 style="color: #a78bfa; margin-bottom: 15px;">Tools & Platforms</h3>
      <div>
        <span class="tech-badge">Git & GitHub</span>
        <span class="tech-badge"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/wordpress/wordpress-original.svg" width="15" class="tech-icon" /> WordPress</span>
        <span class="tech-badge">VS Code</span>
        <span class="tech-badge">Postman</span>
      </div>
    </div>

    <!-- Learning -->
    <div class="card">
      <h3 style="color: #facc15; margin-bottom: 15px;">Currently Learning</h3>
      <div>
        <span class="tech-badge">Advanced AI Models</span>
        <span class="tech-badge">Natural Language Processing</span>
        <span class="tech-badge">System Design</span>
      </div>
    </div>
  </div>

  <!-- CONTRIBUTION SNAKE (Unique Visual) -->
  <div style="text-align: center; margin-top: 40px; overflow: hidden;">
    <img src="https://raw.githubusercontent.com/Syedain-Iqbal-Shigri/Syedain-Iqbal-Shigri/output/github-contribution-grid-snake.svg" alt="Snake Animation" />
  </div>

  <!-- FOOTER -->
  <div class="footer">
    <p style="margin-bottom: 20px;">📫 Connect with me: <a href="mailto:sishigree@gmail.com" style="color: #38bdf8;">sishigree@gmail.com</a></p>
    
    <a href="https://github.com/Syedain-Iqbal-Shigri" class="social-link" title="GitHub">
      <img src="https://img.icons8.com/fluency/48/000000/github.png" width="40" alt="GitHub" />
    </a>
    <a href="mailto:sishigree@gmail.com" class="social-link" title="Email">
      <img src="https://img.icons8.com/fluency/48/000000/new-post.png" width="40" alt="Email" />
    </a>
    <!-- Add LinkedIn here if you have one -->
  </div>

</div>
