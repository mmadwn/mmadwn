### <p align="center" class="gradient-text animate-title">Hey, I'm Ridwan <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="20px" class="wave-animation"></p>

<p align="center" class="gradient-text animate-subtitle">Passionate about creating innovative solutions and learning new technologies ✨</p>

<div class="container animate-fade-in">
  <div class="section hover-lift">
    <h4>🎯 About Me</h4>
    • 🎓 Computer Engineering graduate from Diponegoro University<br>
    • 💻 Exploring Web and Mobile Development<br>
    • 🚀 Open to exciting opportunities in the tech industry
  </div>

  <div class="section hover-lift">
    <h4>🛠️ Skills & Interests</h4>
    • 🎨 Motion Design & Creative Development<br>
    • 👨‍💻 Web and Mobile Development
  </div>

  <div class="section tech-stack hover-lift">
    <h4>🔧 Tech Stack</h4>
    <div align="center">
      <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/-React_Native-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React Native" />
      <img src="https://img.shields.io/badge/-Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white" alt="Framer Motion" />
      <img src="https://img.shields.io/badge/-Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind" />
      <img src="https://img.shields.io/badge/-GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white" alt="GSAP" />
      <img src="https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
      <img src="https://img.shields.io/badge/-PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
      <img src="https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS" />
      <img src="https://img.shields.io/badge/-VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" alt="VSCode" />
      <img src="https://img.shields.io/badge/-Obsidian-483699?style=flat-square&logo=obsidian&logoColor=white" alt="Obsidian" />
    </div>
  </div>

  <div class="section connect hover-lift">
    <h4>🤝 Let's Connect!</h4>
    <div align="center" class="social-links">
      <a href="https://www.linkedin.com/in/mmadwn/" target="_blank">
        <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
      </a>
      <a href="mailto:muh.rdwan.u@gmail.com">
        <img src="https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
      </a>
      <a href="https://discord.com/users/357946202672726016" target="_blank">
        <img src="https://img.shields.io/badge/-Discord-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" />
      </a>
    </div>
  </div>
</div>

<style>
.animate-title {
  animation: slideInFromTop 1s ease-out, gradientFlow 3s infinite;
}

.animate-subtitle {
  animation: fadeIn 1.2s ease-out;
  opacity: 0;
  animation-fill-mode: forwards;
}

.animate-fade-in {
  animation: fadeIn 1.5s ease-out;
}

.wave-animation {
  animation: wave 2s infinite;
  display: inline-block;
}

.hover-lift {
  transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  position: relative;
}

.hover-lift:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.social-links a {
  margin: 0 6px;
  transition: all 0.2s ease;
  display: inline-block;
}

.social-links a:hover {
  transform: scale(1.05) translateY(-2px);
}

@keyframes slideInFromTop {
  0% {
    transform: translateY(-30px);
    opacity: 0;
  }
  100% {
    transform: translateY(0);
    opacity: 1;
  }
}

@keyframes fadeIn {
  0% { opacity: 0; transform: translateY(10px); }
  100% { opacity: 1; transform: translateY(0); }
}

@keyframes wave {
  0%, 100% { transform: rotate(0deg); }
  50% { transform: rotate(15deg); }
}

@keyframes gradientFlow {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

.gradient-text {
  background: linear-gradient(45deg, #FF6B6B, #4ECDC4, #45B7D1);
  background-size: 200% 200%;
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: bold;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.section {
  background: rgba(255, 255, 255, 0.03);
  border-radius: 12px;
  padding: 20px;
  margin: 15px 0;
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.05);
}

.tech-stack img {
  margin: 4px;
  transition: transform 0.2s ease;
}

.tech-stack img:hover {
  transform: translateY(-2px);
}

h4 {
  margin-bottom: 15px;
  color: #4ECDC4;
}
</style>
