<style>
/* Keyframes for animations */
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

@keyframes flyIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes blurIn {
  from {
    opacity: 0;
    filter: blur(10px);
  }
  to {
    opacity: 1;
    filter: blur(0);
  }
}

@keyframes gradientAnimation {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orange; }
}

/* Animation Classes */
.fade-in {
  animation: fadeIn 1.5s ease-in-out forwards;
}

.fly-in {
  animation: flyIn 1s ease-out forwards;
}

.blur-in {
  animation: blurIn 1.2s ease-out forwards;
}

.animated-gradient-text {
  background: linear-gradient(90deg, #36BCF7, #feda75, #fa7e1e, #d62976, #962fbf, #4f5bd5);
  background-size: 200% 200%;
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  animation: gradientAnimation 5s ease infinite;
}

/* Static Typing Effect */
.typing-effect {
  display: inline-block;
  overflow: hidden; 
  border-right: .15em solid orange; /* The typewriter cursor */
  white-space: nowrap;
  margin: 0 auto; 
  letter-spacing: .10em;
  animation: 
    typing 3s steps(30, end) forwards,
    blink-caret .75s step-end infinite;
}


/* Project Card Grid and Hover Effect */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 1rem;
  justify-content: center;
  padding: 10px;
}

.project-card {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}
</style>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=25&duration=4000&pause=1000&color=36BCF7&center=true&vCenter=true&width=435&lines=Hi%2C+I'm+Victor;Welcome+to+my+GitHub+Profile!)](https://git.io/typing-svg)

<div align="center">
  <h1 class="animated-gradient-text">Hi there, I'm Victor 👋</h1>
  <h3 class="fly-in" style="animation-delay: 0.5s;">A passionate developer on a journey of creation and discovery.</h3>
  <p class="fade-in" style="animation-delay: 1s;">I'm currently exploring the worlds of Embedded Systems, AI Robotics, and Linux, and I love building cool things.</p>
</div>

---

<table>
<tr>
<td valign="top" width="65%">

<p align="center">
  <img src="https://img.shields.io/badge/-🚀%20About%20Me%20%2F%20关于我-000000?style=for-the-badge&logo=About.me&logoColor=magenta" alt="About Me Header"/>
</p>

<details>
<summary><strong>&nbsp; 🇨🇳 中文</strong></summary>
<p align="left" style="line-height: 1.8;">
  &nbsp; - 🔭 我目前正致力于：<b>双足轮腿机器人步态算法、嵌入式+AI 机器人系统、边缘计算物联网(IoT)</b>，以及在低功耗、低成本平台上的硬件解决方案。<br>
  &nbsp; - 🌱 我正在深入学习：更高级的<b>机器人路径规划算法</b>与复杂的<b>物联网控制方案</b> (如 Mesh 组网+WIFI)。<br>
  &nbsp; - 👯 我期望能在<b>智能机器人系统、嵌入式物联网</b>或<b>计算机视觉</b>相关的开源项目中进行协作。<br>
  &nbsp; - 🤔 我在为<b>无人驾驶系统寻找最优路径规划方案</b>和<b>实现高可靠性的多设备无线组网通信</b>方面，希望能获得一些帮助与交流。<br>
  &nbsp; - 💬 欢迎与我交流任何关于<b>STM32嵌入式开发、ROS2机器人系统、OpenMV/OpenCV嵌入式视觉应用</b>或<b>CAN/IIC/蓝牙</b>等通信协议的问题。<br>
  &nbsp; - 📫 如何联系我: <b>102450592zzy@gmail.com</b>
</p>
</details>

<details>
<summary><strong>&nbsp; 🇬🇧 English</strong></summary>
<p align="left" style="line-height: 1.8;">
  &nbsp; - 🔭 I’m currently working on: <b>Gait algorithms for bipedal wheeled robots, Embedded+AI Robotics systems, Edge Computing & IoT</b>, and hardware solutions for low-power, low-cost platforms.<br>
  &nbsp; - 🌱 I’m currently learning: More advanced <b>robot path planning algorithms</b> & complex <b>IoT control schemes</b> (like Mesh networking + WIFI).<br>
  &nbsp; - 👯 I’m looking to collaborate on open-source projects related to <b>intelligent robot systems, embedded IoT, or computer vision</b>.<br>
  &nbsp; - 🤔 I’m looking for help with: Finding optimal <b>path planning solutions for autonomous driving systems</b> and implementing highly reliable <b>multi-device wireless network communications</b>.<br>
  &nbsp; - 💬 Ask me about: <b>STM32 embedded development, ROS2 robot systems, OpenMV/OpenCV embedded vision applications</b>, or communication protocols like <b>CAN/IIC/Bluetooth</b>.<br>
  &nbsp; - 📫 How to reach me: <b>102450592zzy@gmail.com</b>
</p>
</details>
<br>

<p align="center">
  <img src="https://img.shields.io/badge/-✨%20My%20Projects%20%2F%20我的项目-000000?style=for-the-badge&logo=GitHub&logoColor=cyan" alt="My Projects Header"/>
</p>

<div class="projects-grid">
  <a href="https://github.com/12sqawdwq/fractal_flower" target="_blank" class="project-card">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=12sqawdwq&repo=fractal_flower&theme=synthwave&description_lines_count=2" alt="Fractal Flower (Linux ASCII Art)" />
  </a>
  <a href="https://github.com/12sqawdwq/PI-CAI_TransUnet" target="_blank" class="project-card">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=12sqawdwq&repo=PI-CAI_TransUnet&theme=synthwave&description_lines_count=2" alt="PI-CAI TransUnet" />
  </a>
  <a href="https://github.com/12sqawdwq/Augmentation" target="_blank" class="project-card">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=12sqawdwq&repo=Augmentation&theme=synthwave&description_lines_count=2" alt="Data Augmentation" />
  </a>
  <a href="https://github.com/12sqawdwq/DJI-dev-board-c-imu" target="_blank" class="project-card">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=12sqawdwq&repo=DJI-dev-board-c-imu&theme=synthwave&description_lines_count=2" alt="DJI IMU" />
  </a>
</div>

</td>
<td valign="top" width="35%">

<p align="center">
  <img src="https://img.shields.io/badge/-🛠️%20Tech%20Stack-000000?style=for-the-badge&logo=Power-Automate&logoColor=lime" alt="Tech Stack Header"/>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,linux,ros,qt,js,react,nodejs,docker,git,vscode&perline=4&theme=dark" alt="My Tech Stack"/>
</p>
<br>

<p align="center">
  <img src="https://img.shields.io/badge/-🏆%20GitHub%20Trophies-000000?style=for-the-badge&logo=Trophy&logoColor=gold" alt="GitHub Trophies Header"/>
</p>
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=12sqawdwq&theme=synthwave&column=4&margin-w=15&margin-h=15&no-frame=true" alt="GitHub Trophies"/>
</p>
<br>

<p align="center">
  <img src="https://img.shields.io/badge/-📊%20GitHub%20Stats-000000?style=for-the-badge&logo=GitHub-Actions&logoColor=yellow" alt="GitHub Stats Header"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=12sqawdwq&show_icons=true&theme=synthwave&icon_color=79ff97&hide_border=true&count_private=true&rank_icon=github" alt="Victor's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=12sqawdwq&layout=compact&theme=synthwave&hide_border=true&langs_count=8" alt="Victor's Top Languages" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=12sqawdwq&theme=synthwave&hide_border=true" alt="GitHub Streak" />
</p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=12sqawdwq&style=for-the-badge&color=blueviolet" alt="Profile Views"/>
</p>

</td>
</tr>
</table>

---

<p align="center">
  <a href="mailto:102450592zzy@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/12sqawdwq/12sqawdwq/main/dist/github-contribution-grid-snake-dark.svg?palette=github-dark" alt="contribution snake" />
</p>
