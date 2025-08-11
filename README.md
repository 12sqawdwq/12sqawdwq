<style>
/* ====== 1. 全局布局：使用现代化的Flexbox进行两栏布局 ====== */
.profile-container {
  display: flex;
  flex-wrap: wrap; /* 在小屏幕上会自动换行，实现响应式 */
  gap: 20px;     /* 设置左右两栏的间距 */
}
.left-column {
  flex: 1; /* 占据1份空间 */
  min-width: 320px;
}
.right-column {
  flex: 2; /* 占据2份空间，更宽一些 */
  min-width: 350px;
}

/* ====== 2. 项目卡片网格与动画 ====== */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 16px;
}

@keyframes card-entry {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.project-card {
  display: block;
  transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
  opacity: 0;
  animation: card-entry 0.6s ease-out forwards;
}

.project-card:hover {
  transform: scale(1.05) translateY(-5px);
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
}

/* 为项目卡片设置错开的入场动画延迟 */
.projects-grid .project-card:nth-child(1) { animation-delay: 0.1s; }
.projects-grid .project-card:nth-child(2) { animation-delay: 0.2s; }
.projects-grid .project-card:nth-child(3) { animation-delay: 0.3s; }
.projects-grid .project-card:nth-child(4) { animation-delay: 0.4s; }
</style>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=25&duration=4000&pause=1000&color=36BCF7&center=true&vCenter=true&width=435&lines=Hi%2C+I'm+Victor;Welcome+to+my+GitHub+Profile!" alt="Typing SVG" />
  </a>
  <h1>Hi there, I'm Victor 👋</h1>
  <h3>A passionate developer on a journey of creation and discovery.</h3>
  <p>I'm currently exploring the worlds of Embedded Systems, AI Robotics, and Linux, and I love building cool things.</p>
</div>

<hr />

<div class="profile-container">

  <div class="left-column">
    <h2 align="center">⚡ My GitHub Stats ⚡</h2>
    <p align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=12sqawdwq&show_icons=true&theme=synthwave&icon_color=79ff97&hide_border=true&count_private=true&rank_icon=github" alt="Victor's GitHub Stats" />
    </p>
    <p align="center">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=12sqawdwq&layout=compact&theme=synthwave&hide_border=true&langs_count=8" alt="Victor's Top Languages" />
    </p>
    <p align="center">
      <img src="https://streak-stats.demolab.com/?user=12sqawdwq&theme=synthwave&hide_border=true" alt="GitHub Streak" />
    </p>
    <p align="center">
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=12sqawdwq&theme=synthwave&bg_color=2b213a&hide_border=true&color=79ff97&line=9e4c98&point=e0c28a" width="100%"/>
    </p>
    <p align="center">
      <img src="https://komarev.com/ghpvc/?username=12sqawdwq&style=for-the-badge&color=blueviolet" alt="Profile Views"/>
    </p>
  </div>

  <div class="right-column">
    <p align="center">
      <img src="https://img.shields.io/badge/-🚀%20About%20Me%20%2F%20关于我-000000?style=for-the-badge&logo=About.me&logoColor=magenta" alt="About Me Header"/>
    </p>
    <details>
      <summary><strong>&nbsp; 🇨🇳 中文</strong></summary>
      <p align="left" style="line-height: 1.8;">
        &nbsp; - 🔭 我目前正致力于：<b>双足轮腿机器人步态算法、嵌入式+AI 机器人系统、边缘计算物联网(IoT)</b>...<br>
        &nbsp; - 🌱 我正在深入学习：更高级的<b>机器人路径规划算法</b>与复杂的<b>物联网控制方案</b>...<br>
        &nbsp; - 👯 我期望能在<b>智能机器人系统、嵌入式物联网</b>或<b>计算机视觉</b>相关的开源项目中进行协作。<br>
        &nbsp; - 🤔 我在为<b>无人驾驶系统寻找最优路径规划方案</b>和<b>实现高可靠性的多设备无线组网通信</b>方面寻求帮助。<br>
        &nbsp; - 💬 欢迎与我交流任何关于<b>STM32、ROS2、OpenMV/OpenCV</b>或<b>通信协议</b>的问题。<br>
        &nbsp; - 📫 如何联系我: <b>102450592zzy@gmail.com</b>
      </p>
    </details>
    <details>
      <summary><strong>&nbsp; 🇬🇧 English</strong></summary>
      <p align="left" style="line-height: 1.8;">
        &nbsp; - 🔭 I’m currently working on: <b>Gait algorithms for bipedal wheeled robots, Embedded+AI Robotics systems...</b><br>
        &nbsp; - 🌱 I’m currently learning: More advanced <b>robot path planning algorithms & complex IoT control schemes...</b><br>
        &nbsp; - 👯 I’m looking to collaborate on projects related to <b>intelligent robot systems, embedded IoT, or computer vision</b>.<br>
        &nbsp; - 🤔 I’m looking for help with: Optimal <b>path planning for autonomous systems</b> & reliable <b>multi-device wireless networking</b>.<br>
        &nbsp; - 💬 Ask me about: <b>STM32, ROS2, OpenMV/OpenCV,</b> or communication protocols.<br>
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
    <br>
    <p align="center">
      <img src="https://img.shields.io/badge/-🛠️%20Tech%20Stack-000000?style=for-the-badge&logo=Power-Automate&logoColor=lime" alt="Tech Stack Header"/>
    </p>
    <p align="center">
      <img src="https://skillicons.dev/icons?i=c,cpp,python,linux,ros,qt,js,react,nodejs,docker,git,vscode&perline=6&theme=dark" alt="My Tech Stack"/>
    </p>
    <br>
    <p align="center">
      <img src="https://img.shields.io/badge/-🏆%20GitHub%20Trophies-000000?style=for-the-badge&logo=Trophy&logoColor=gold" alt="GitHub Trophies Header"/>
    </p>
    <p align="center">
      <img src="https://github-profile-trophy.vercel.app/?username=12sqawdwq&theme=synthwave&column=5&margin-w=15&margin-h=15&no-frame=true" alt="GitHub Trophies"/>
    </p>
  </div>
</div>

<hr />

<p align="center">
  <a href="mailto:102450592zzy@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/12sqawdwq/12sqawdwq/main/dist/github-contribution-grid-snake-dark.svg?palette=github-dark" alt="contribution snake" />
</p>
