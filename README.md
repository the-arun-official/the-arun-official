<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;600;700&family=Syne:wght@400;700;800&display=swap');

:root {
  --primary-gradient: linear-gradient(135deg, #00d4ff 0%, #0099ff 100%);
  --secondary-gradient: linear-gradient(135deg, #ff006e 0%, #8338ec 100%);
  --neon-cyan: #00d4ff;
  --neon-pink: #ff006e;
  --neon-purple: #8338ec;
  --dark-bg: #0a0e27;
  --glass: rgba(255, 255, 255, 0.05);
}
</style>

<div align="center">

<!-- Animated Header -->
<svg width="100%" height="200" viewBox="0 0 1000 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="gradientText" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:1">
        <animate attributeName="stop-color" values="#00d4ff;#8338ec;#ff006e;#00d4ff" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#ff006e;stop-opacity:1">
        <animate attributeName="stop-color" values="#ff006e;#00d4ff;#8338ec;#ff006e" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <text x="500" y="100" font-size="72" font-weight="900" text-anchor="middle" fill="url(#gradientText)" filter="url(#glow)" font-family="Space Grotesk">
    ARUN PALANISAMY
  </text>
  
  <text x="500" y="160" font-size="24" text-anchor="middle" fill="#00d4ff" font-family="Space Grotesk" opacity="0.8">
    <tspan>✨ Full-Stack Developer | Code Architect ✨</tspan>
  </text>
  
  <!-- Animated line -->
  <line x1="100" y1="175" x2="900" y2="175" stroke="#00d4ff" stroke-width="2" opacity="0.5">
    <animate attributeName="x1" values="100;200;100" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="900;800;900" dur="3s" repeatCount="indefinite"/>
  </line>
</svg>

---

<!-- Modern Badge Section -->
<div style="display: flex; justify-content: center; gap: 12px; flex-wrap: wrap; margin: 30px 0;">
  <img src="https://img.shields.io/badge/REACT-61DAFB?style=for-the-badge&logo=react&logoColor=000&labelColor=0a0e27&color=00d4ff" alt="React" />
  <img src="https://img.shields.io/badge/NODE.JS-339933?style=for-the-badge&logo=node.js&logoColor=fff&labelColor=0a0e27&color=00d4ff" alt="Node.js" />
  <img src="https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge&logo=typescript&logoColor=fff&labelColor=0a0e27&color=00d4ff" alt="TypeScript" />
  <img src="https://img.shields.io/badge/POSTGRESQL-336791?style=for-the-badge&logo=postgresql&logoColor=fff&labelColor=0a0e27&color=00d4ff" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/EXPRESS-000?style=for-the-badge&logo=express&logoColor=fff&labelColor=0a0e27&color=ff006e" alt="Express" />
</div>

---

</div>

## 🎯 ABOUT ME

<table style="width:100%; border-collapse: collapse;">
  <tr>
    <td style="padding: 20px; background: linear-gradient(135deg, rgba(0,212,255,0.1) 0%, rgba(131,56,236,0.1) 100%); border: 1px solid rgba(0,212,255,0.3); border-radius: 12px;">
      <h3 style="color: #00d4ff; margin-top: 0;">💡 THE VISION</h3>
      <p style="color: #e0e0e0; line-height: 1.8;">
        I'm a passionate developer on a mission to build <strong>scalable, user-centric applications</strong> that make a real impact. With deep expertise in the PERN stack, I transform ideas into elegant digital solutions.
      </p>
    </td>
  </tr>
</table>

---

## 🚀 TECH ARSENAL

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 15px; margin: 30px 0;">

<!-- Frontend Card -->
<div style="background: linear-gradient(135deg, rgba(0,212,255,0.1) 0%, rgba(0,212,255,0.05) 100%); border: 2px solid rgba(0,212,255,0.3); border-radius: 12px; padding: 20px; backdrop-filter: blur(10px); transition: all 0.3s ease;">
  <h4 style="color: #00d4ff; margin-top: 0; font-size: 16px;">⚡ FRONTEND</h4>
  <div style="color: #b0b0b0; font-size: 13px; line-height: 1.8;">
    • React.js<br>
    • TypeScript<br>
    • Responsive UI<br>
    • Modern CSS
  </div>
</div>

<!-- Backend Card -->
<div style="background: linear-gradient(135deg, rgba(255,0,110,0.1) 0%, rgba(255,0,110,0.05) 100%); border: 2px solid rgba(255,0,110,0.3); border-radius: 12px; padding: 20px; backdrop-filter: blur(10px);">
  <h4 style="color: #ff006e; margin-top: 0; font-size: 16px;">🔧 BACKEND</h4>
  <div style="color: #b0b0b0; font-size: 13px; line-height: 1.8;">
    • Node.js<br>
    • Express.js<br>
    • REST APIs<br>
    • Authentication
  </div>
</div>

<!-- Database Card -->
<div style="background: linear-gradient(135deg, rgba(131,56,236,0.1) 0%, rgba(131,56,236,0.05) 100%); border: 2px solid rgba(131,56,236,0.3); border-radius: 12px; padding: 20px; backdrop-filter: blur(10px);">
  <h4 style="color: #8338ec; margin-top: 0; font-size: 16px;">💾 DATABASE</h4>
  <div style="color: #b0b0b0; font-size: 13px; line-height: 1.8;">
    • PostgreSQL<br>
    • Schema Design<br>
    • Optimization<br>
    • Query Mastery
  </div>
</div>

<!-- Tools Card -->
<div style="background: linear-gradient(135deg, rgba(0,212,255,0.1) 0%, rgba(255,0,110,0.1) 100%); border: 2px solid rgba(0,212,255,0.3); border-radius: 12px; padding: 20px; backdrop-filter: blur(10px);">
  <h4 style="color: #00d4ff; margin-top: 0; font-size: 16px;">🛠️ TOOLS</h4>
  <div style="color: #b0b0b0; font-size: 13px; line-height: 1.8;">
    • Git/GitHub<br>
    • Postman<br>
    • VS Code<br>
    • Debugging
  </div>
</div>

</div>

---

## 📊 SKILLS MATRIX

<div style="background: linear-gradient(135deg, rgba(0,212,255,0.05) 0%, rgba(131,56,236,0.05) 100%); border: 2px solid rgba(0,212,255,0.2); border-radius: 16px; padding: 30px; margin: 30px 0; backdrop-filter: blur(10px);">

| Skill | Proficiency | Level |
|-------|-------------|-------|
| **React.js** | ████████████████████ | ⭐⭐⭐⭐⭐ |
| **Node.js & Express** | ████████████████████ | ⭐⭐⭐⭐⭐ |
| **PostgreSQL** | ████████████████████ | ⭐⭐⭐⭐⭐ |
| **TypeScript** | ██████████████████░░ | ⭐⭐⭐⭐☆ |
| **REST API Development** | ████████████████████ | ⭐⭐⭐⭐⭐ |
| **Authentication Systems** | ████████████████████ | ⭐⭐⭐⭐⭐ |
| **Responsive Design** | ██████████████████░░ | ⭐⭐⭐⭐☆ |
| **Cloud Deployment** | █████████░░░░░░░░░░░ | ⭐⭐⭐☆☆ |

</div>

---

## 💥 CORE COMPETENCIES

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 30px 0;">

<!-- Left Column -->
<div>
  <div style="background: linear-gradient(135deg, rgba(0,212,255,0.1) 0%, transparent 100%); border-left: 4px solid #00d4ff; padding: 20px; margin: 10px 0; border-radius: 8px;">
    <h4 style="color: #00d4ff; margin: 0 0 10px 0;">⚙️ FULL-STACK MASTERY</h4>
    <p style="color: #d0d0d0; margin: 0; font-size: 14px;">End-to-end application development from database to UI, with production-ready code quality.</p>
  </div>

  <div style="background: linear-gradient(135deg, rgba(255,0,110,0.1) 0%, transparent 100%); border-left: 4px solid #ff006e; padding: 20px; margin: 10px 0; border-radius: 8px;">
    <h4 style="color: #ff006e; margin: 0 0 10px 0;">🧠 PROBLEM SOLVING</h4>
    <p style="color: #d0d0d0; margin: 0; font-size: 14px;">Breaking complex challenges into elegant solutions with optimized performance.</p>
  </div>

  <div style="background: linear-gradient(135deg, rgba(131,56,236,0.1) 0%, transparent 100%); border-left: 4px solid #8338ec; padding: 20px; margin: 10px 0; border-radius: 8px;">
    <h4 style="color: #8338ec; margin: 0 0 10px 0;">🔐 SECURE SYSTEMS</h4>
    <p style="color: #d0d0d0; margin: 0; font-size: 14px;">Implementing JWT, OTP, and modern authentication & authorization patterns.</p>
  </div>
</div>

<!-- Right Column -->
<div>
  <div style="background: linear-gradient(135deg, rgba(0,212,255,0.1) 0%, transparent 100%); border-left: 4px solid #00d4ff; padding: 20px; margin: 10px 0; border-radius: 8px;">
    <h4 style="color: #00d4ff; margin: 0 0 10px 0;">🚀 SCALABILITY</h4>
    <p style="color: #d0d0d0; margin: 0; font-size: 14px;">Designing architectures that grow with your application demands.</p>
  </div>

  <div style="background: linear-gradient(135deg, rgba(255,0,110,0.1) 0%, transparent 100%); border-left: 4px solid #ff006e; padding: 20px; margin: 10px 0; border-radius: 8px;">
    <h4 style="color: #ff006e; margin: 0 0 10px 0;">🎯 CODE QUALITY</h4>
    <p style="color: #d0d0d0; margin: 0; font-size: 14px;">Clean, maintainable, and well-documented code following best practices.</p>
  </div>

  <div style="background: linear-gradient(135deg, rgba(131,56,236,0.1) 0%, transparent 100%); border-left: 4px solid #8338ec; padding: 20px; margin: 10px 0; border-radius: 8px;">
    <h4 style="color: #8338ec; margin: 0 0 10px 0;">📚 CONTINUOUS LEARNING</h4>
    <p style="color: #d0d0d0; margin: 0; font-size: 14px;">Staying ahead of trends and mastering emerging technologies rapidly.</p>
  </div>
</div>

</div>

---

## 🎨 DEVELOPMENT FLOW

<svg width="100%" height="200" viewBox="0 0 1000 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="flowGrad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#0099ff;stop-opacity:1"/>
    </linearGradient>
    <linearGradient id="flowGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff006e;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#8338ec;stop-opacity:1"/>
    </linearGradient>
  </defs>
  
  <!-- Step 1 -->
  <circle cx="100" cy="100" r="40" fill="url(#flowGrad1)" opacity="0.8">
    <animate attributeName="r" values="40;45;40" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="100" y="110" text-anchor="middle" fill="white" font-size="24" font-weight="bold">1</text>
  <text x="100" y="160" text-anchor="middle" fill="#00d4ff" font-size="14">IDEATE</text>
  
  <!-- Arrow 1 -->
  <line x1="150" y1="100" x2="250" y2="100" stroke="url(#flowGrad1)" stroke-width="3">
    <animate attributeName="x2" values="250;280;250" dur="2s" repeatCount="indefinite"/>
  </line>
  
  <!-- Step 2 -->
  <circle cx="300" cy="100" r="40" fill="url(#flowGrad2)" opacity="0.8">
    <animate attributeName="r" values="40;45;40" dur="2s" repeatCount="indefinite" begin="0.5s"/>
  </circle>
  <text x="300" y="110" text-anchor="middle" fill="white" font-size="24" font-weight="bold">2</text>
  <text x="300" y="160" text-anchor="middle" fill="#ff006e" font-size="14">DESIGN</text>
  
  <!-- Arrow 2 -->
  <line x1="350" y1="100" x2="450" y2="100" stroke="url(#flowGrad1)" stroke-width="3">
    <animate attributeName="x2" values="450;480;450" dur="2s" repeatCount="indefinite"/>
  </line>
  
  <!-- Step 3 -->
  <circle cx="500" cy="100" r="40" fill="url(#flowGrad1)" opacity="0.8">
    <animate attributeName="r" values="40;45;40" dur="2s" repeatCount="indefinite" begin="1s"/>
  </circle>
  <text x="500" y="110" text-anchor="middle" fill="white" font-size="24" font-weight="bold">3</text>
  <text x="500" y="160" text-anchor="middle" fill="#00d4ff" font-size="14">BUILD</text>
  
  <!-- Arrow 3 -->
  <line x1="550" y1="100" x2="650" y2="100" stroke="url(#flowGrad2)" stroke-width="3">
    <animate attributeName="x2" values="650;680;650" dur="2s" repeatCount="indefinite"/>
  </line>
  
  <!-- Step 4 -->
  <circle cx="700" cy="100" r="40" fill="url(#flowGrad2)" opacity="0.8">
    <animate attributeName="r" values="40;45;40" dur="2s" repeatCount="indefinite" begin="1.5s"/>
  </circle>
  <text x="700" y="110" text-anchor="middle" fill="white" font-size="24" font-weight="bold">4</text>
  <text x="700" y="160" text-anchor="middle" fill="#ff006e" font-size="14">TEST</text>
  
  <!-- Arrow 4 -->
  <line x1="750" y1="100" x2="850" y2="100" stroke="url(#flowGrad1)" stroke-width="3">
    <animate attributeName="x2" values="850;880;850" dur="2s" repeatCount="indefinite"/>
  </line>
  
  <!-- Step 5 -->
  <circle cx="900" cy="100" r="40" fill="url(#flowGrad1)" opacity="0.8">
    <animate attributeName="r" values="40;45;40" dur="2s" repeatCount="indefinite" begin="2s"/>
  </circle>
  <text x="900" y="110" text-anchor="middle" fill="white" font-size="24" font-weight="bold">5</text>
  <text x="900" y="160" text-anchor="middle" fill="#00d4ff" font-size="14">DEPLOY</text>
</svg>

---

## 📈 IMPACT METRICS

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 15px; margin: 30px 0;">

<div style="background: linear-gradient(135deg, rgba(0,212,255,0.15) 0%, rgba(0,212,255,0.05) 100%); border: 2px solid rgba(0,212,255,0.4); border-radius: 12px; padding: 20px; text-align: center; backdrop-filter: blur(10px);">
  <div style="font-size: 36px; color: #00d4ff; font-weight: 900; margin-bottom: 8px;">5+</div>
  <div style="color: #b0b0b0; font-size: 12px; font-weight: 600;">PROJECTS SHIPPED</div>
</div>

<div style="background: linear-gradient(135deg, rgba(255,0,110,0.15) 0%, rgba(255,0,110,0.05) 100%); border: 2px solid rgba(255,0,110,0.4); border-radius: 12px; padding: 20px; text-align: center; backdrop-filter: blur(10px);">
  <div style="font-size: 36px; color: #ff006e; font-weight: 900; margin-bottom: 8px;">15+</div>
  <div style="color: #b0b0b0; font-size: 12px; font-weight: 600;">TECH MASTERED</div>
</div>

<div style="background: linear-gradient(135deg, rgba(131,56,236,0.15) 0%, rgba(131,56,236,0.05) 100%); border: 2px solid rgba(131,56,236,0.4); border-radius: 12px; padding: 20px; text-align: center; backdrop-filter: blur(10px);">
  <div style="font-size: 36px; color: #8338ec; font-weight: 900; margin-bottom: 8px;">2+</div>
  <div style="color: #b0b0b0; font-size: 12px; font-weight: 600;">YEARS LEARNING</div>
</div>

<div style="background: linear-gradient(135deg, rgba(0,212,255,0.15) 0%, rgba(131,56,236,0.15) 100%); border: 2px solid rgba(0,212,255,0.4); border-radius: 12px; padding: 20px; text-align: center; backdrop-filter: blur(10px);">
  <div style="font-size: 36px; color: #00d4ff; font-weight: 900; margin-bottom: 8px;">∞</div>
  <div style="color: #b0b0b0; font-size: 12px; font-weight: 600;">GROWTH MINDSET</div>
</div>

</div>

---

## 🎯 WHY CHOOSE ME?

<div style="background: linear-gradient(135deg, rgba(0,212,255,0.08) 0%, rgba(131,56,236,0.08) 100%); border: 2px solid rgba(0,212,255,0.3); border-radius: 16px; padding: 40px; margin: 30px 0; position: relative; overflow: hidden;">

<div style="position: relative; z-index: 1;">

```
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃                                                       ┃
┃  ✅  Full-Stack PERN Architecture Expert            ┃
┃  ✅  Scalable & Production-Ready Solutions          ┃
┃  ✅  Secure Authentication & Authorization Systems  ┃
┃  ✅  Clean, Maintainable Code Philosophy            ┃
┃  ✅  Problem-Solving with Elegant Implementations   ┃
┃  ✅  Rapid Technology Adoption & Mastery            ┃
┃  ✅  Collaborative Team Player                      ┃
┃  ✅  Performance Optimization Focused               ┃
┃                                                       ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```

</div>

</div>

---

## 💼 LET'S COLLABORATE

<div align="center">

<table>
  <tr>
    <td colspan="3" style="padding: 20px; text-align: center;">
      <h2 style="color: #00d4ff; margin: 0; font-size: 28px;">🚀 READY TO BUILD SOMETHING AMAZING?</h2>
      <p style="color: #b0b0b0; margin: 10px 0 0 0;">Let's create groundbreaking digital experiences together</p>
    </td>
  </tr>
  <tr>
    <td style="padding: 20px; background: linear-gradient(135deg, rgba(0,212,255,0.1) 0%, transparent 100%); border: 2px solid rgba(0,212,255,0.3); border-radius: 12px; text-align: center;">
      <strong style="color: #00d4ff;">📧 EMAIL</strong><br>
      <a href="mailto:csarun866@gmail.com" style="color: #00d4ff; text-decoration: none; font-size: 14px;">csarun866@gmail.com</a>
    </td>
    <td style="padding: 20px; background: linear-gradient(135deg, rgba(255,0,110,0.1) 0%, transparent 100%); border: 2px solid rgba(255,0,110,0.3); border-radius: 12px; text-align: center; margin: 0 15px;">
      <strong style="color: #ff006e;">💼 LINKEDIN</strong><br>
      <a href="https://linkedin.com/in/arunpalanisamy" style="color: #ff006e; text-decoration: none; font-size: 14px;">Arun Palanisamy</a>
    </td>
    <td style="padding: 20px; background: linear-gradient(135deg, rgba(131,56,236,0.1) 0%, transparent 100%); border: 2px solid rgba(131,56,236,0.3); border-radius: 12px; text-align: center;">
      <strong style="color: #8338ec;">🐙 GITHUB</strong><br>
      <a href="https://github.com/arunpalanisamy" style="color: #8338ec; text-decoration: none; font-size: 14px;">GitHub Profile</a>
    </td>
  </tr>
</table>

</div>

---

## 🌟 MY DEVELOPMENT PHILOSOPHY

<svg width="100%" height="120" viewBox="0 0 1000 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="philoGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#ff006e;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#8338ec;stop-opacity:1"/>
    </linearGradient>
  </defs>
  
  <text x="500" y="50" text-anchor="middle" fill="url(#philoGrad)" font-size="32" font-weight="bold" font-family="Space Grotesk">
    "Code is poetry. Build with purpose."
  </text>
  
  <!-- Pulsing dots -->
  <circle cx="200" cy="100" r="4" fill="#00d4ff">
    <animate attributeName="r" values="4;8;4" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="100" r="4" fill="#ff006e">
    <animate attributeName="r" values="4;8;4" dur="1.5s" repeatCount="indefinite" begin="0.5s"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite" begin="0.5s"/>
  </circle>
  <circle cx="800" cy="100" r="4" fill="#8338ec">
    <animate attributeName="r" values="4;8;4" dur="1.5s" repeatCount="indefinite" begin="1s"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite" begin="1s"/>
  </circle>
</svg>

---

## 📊 GITHUB STATS

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=arunpalanisamy&theme=highcontrast&background=0a0e27&ring=00d4ff&fire=ff006e&currStreakNum=00d4ff&sideNums=00d4ff&currStreakLabel=8338ec&dates=b0b0b0)](https://github.com/arunpalanisamy)

</div>

---

<div align="center" style="margin-top: 50px; padding: 30px; background: linear-gradient(135deg, rgba(0,212,255,0.1) 0%, rgba(131,56,236,0.1) 100%); border-radius: 16px; border: 2px solid rgba(0,212,255,0.2);">

<h3 style="color: #00d4ff; margin-top: 0;">✨ CRAFTING THE FUTURE, ONE LINE OF CODE AT A TIME ✨</h3>

<p style="color: #b0b0b0; font-size: 14px; margin: 15px 0;">
  💻 Building tomorrow's applications today<br>
  🚀 Turning visionary ideas into scalable solutions<br>
  🎯 Committed to excellence and continuous innovation<br>
</p>

<div style="margin-top: 20px;">
  <img src="https://img.shields.io/badge/Made%20with%20❤️%20and%20☕-0a0e27?style=for-the-badge" alt="Made with love and coffee" />
</div>

</div>

---

<div align="center" style="margin-top: 30px; color: #8338ec; font-size: 12px;">

**© 2024 Arun Palanisamy | Architecting Digital Excellence**

</div>
