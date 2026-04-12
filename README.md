<!--
  Nord 配色 · 轻量雪花主题 GitHub 主页
-->

<div class="nord-wrapper">
  <div class="snowfield" aria-hidden="true">
    <div class="snow">❄️</div><div class="snow">❄️</div><div class="snow">❄️</div>
    <div class="snow">❄️</div><div class="snow">❄️</div><div class="snow">❄️</div>
    <div class="snow">❄️</div><div class="snow">❄️</div><div class="snow">❄️</div>
    <div class="snow">❄️</div><div class="snow">❄️</div><div class="snow">❄️</div>
  </div>

  <div class="content">
    <h1 align="center">
      Hi there 👋 · 你好<br>
      <span class="accent">exyone-labs</span>
    </h1>

    <p align="center">
      <strong>❄️ Snowflake & Code Lab ❄️</strong><br>
      .NET 桌面开发 · ASP.NET · Node.js  |  开源爱好者 · 全栈探索者
    </p>

    <hr class="nord-hr">

    <div class="highlight-block">
      🌟 <strong>欢迎大家来访问 / Welcome to my primary tech hub</strong> 🌟<br>
      🚀 <span class="big-link">👉 <a href="https://git.exyone.me" target="_blank">git.exyone.me</a> 👈</span><br>
      <span class="note">Tech notes, experiments & first publications</span>
    </div>

    <hr class="nord-hr">

    <h2>📡 Digital Outposts</h2>
    <p>
      🌐 中文博客 / CN blog: <a href="https://www.exyone.me">www.exyone.me</a><br>
      🌍 英文博客 / EN blog: <a href="https://exyone.is-a.dev">exyone.is-a.dev</a><br>
      ☁️ Cloudflare Pages 镜像: <a href="https://exyone.pages.dev">exyone.pages.dev</a>
    </p>

    <h2>📫 联系方式 · Contact</h2>
    <p>
      ✉️ <a href="mailto:exyone.dev@icloud.com">exyone.dev@icloud.com</a> · 
      <a href="mailto:exyone.dev@yandex.com">exyone.dev@yandex.com</a> · 
      <a href="mailto:root@exyone.me">root@exyone.me</a>
    </p>

    <h2>🪶 其他代码托管平台 · Other Forges</h2>
    <p>
      Gitee: <a href="https://gitee.com/exyone">@exyone</a> &nbsp;|&nbsp;
      Codeberg: <a href="https://codeberg.org/exyone">@exyone</a> &nbsp;|&nbsp;
      Framagit: <a href="https://framagit.org/exyone">@exyone</a> &nbsp;|&nbsp;
    </p>

    <h2>🛠️ 技术栈 · Tech Stack</h2>
    <p>
      <code>.NET 桌面开发</code> <code>ASP.NET Core</code> <code>Node.js</code><br>
      <span class="small">(Desktop, Web API, Backend services)</span>
    </p>

    <hr class="nord-hr">

    <div align="center">
      <img height="170em" src="https://github-readme-stats.vercel.app/api?username=exyone-labs&show_icons=true&theme=nord&hide_border=true&bg_color=2E3440&title_color=81A1C1&icon_color=88C0D0&text_color=D8DEE9" />
      <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=exyone-labs&layout=compact&theme=nord&hide_border=true&bg_color=2E3440&title_color=81A1C1&text_color=D8DEE9" />
    </div>
    <div align="center" style="margin-top: 12px;">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=exyone-labs&theme=nord&hide_border=true&background=2E3440&ring=81A1C1&fire=88C0D0&currStreakLabel=81A1C1" width="70%" />
    </div>

    <hr class="nord-hr">

    <div align="center">
      <img src="https://komarev.com/ghpvc/?username=exyone-labs&label=❄️%20访客%20Snow%20Visitors&color=81A1C1&style=flat-square" alt="visitors" />
      <p class="footer-note">
        ❄️ Snow falls silent, code takes shape.<br>
        <i>always open</i>
      </p>
    </div>
  </div>
</div>

<style>
:root {
  --nord0: #D8DEE9;
  --nord1: #E5E9F0;
  --nord2: #ECEFF4;
  --nord3: #81A1C1;
  --nord4: #2E3440;
  --nord5: #3B4252;
  --nord6: #434C5E;
  --nord7: #8FBCBB;
  --nord8: #88C0D0;
  --nord9: #81A1C1;
  --nord10: #5E81AC;
  --nord11: #BF616A;
  --nord12: #D08770;
  --nord13: #EBCB8B;
  --nord14: #A3BE8C;
  --nord15: #B48EAD;
}

.nord-wrapper {
  position: relative;
  background-color: var(--nord0);
  color: var(--nord4);
  font-family: system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
  line-height: 1.5;
  padding: 2rem 1.5rem;
  margin: 0;
  overflow-x: hidden;
  border-radius: 0;
}

.snowfield {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 0;
  overflow: hidden;
}

.snow {
  position: absolute;
  top: -20px;
  font-size: 1.2rem;
  color: var(--nord6);
  opacity: 0.6;
  user-select: none;
  animation: fallSnow linear infinite;
}

.snow:nth-child(1) { left: 5%; animation-duration: 12s; animation-delay: 0s; }
.snow:nth-child(2) { left: 15%; animation-duration: 16s; animation-delay: 2s; font-size: 1rem; }
.snow:nth-child(3) { left: 25%; animation-duration: 10s; animation-delay: 4s; opacity: 0.8; }
.snow:nth-child(4) { left: 35%; animation-duration: 18s; animation-delay: 1s; font-size: 1.4rem; }
.snow:nth-child(5) { left: 45%; animation-duration: 14s; animation-delay: 5s; }
.snow:nth-child(6) { left: 55%; animation-duration: 20s; animation-delay: 3s; opacity: 0.5; }
.snow:nth-child(7) { left: 65%; animation-duration: 11s; animation-delay: 7s; font-size: 1.1rem; }
.snow:nth-child(8) { left: 75%; animation-duration: 15s; animation-delay: 0.5s; }
.snow:nth-child(9) { left: 85%; animation-duration: 13s; animation-delay: 6s; font-size: 0.9rem; }
.snow:nth-child(10){ left: 95%; animation-duration: 17s; animation-delay: 2.5s; }
.snow:nth-child(11){ left: 10%; animation-duration: 22s; animation-delay: 8s; opacity: 0.7; }
.snow:nth-child(12){ left: 70%; animation-duration: 9s;  animation-delay: 4s; font-size: 1.3rem; }

@keyframes fallSnow {
  0%   { transform: translateY(-20px) rotate(0deg); opacity: 0; }
  10%  { opacity: 0.8; }
  90%  { opacity: 0.8; }
  100% { transform: translateY(100vh) rotate(360deg); opacity: 0; }
}

.content {
  position: relative;
  z-index: 2;
  max-width: 880px;
  margin: 0 auto;
  background: transparent;
  padding: 0.5rem;
}

a {
  color: var(--nord9);
  text-decoration: none;
  border-bottom: 1px dotted var(--nord10);
  transition: color 0.2s;
}
a:hover {
  color: var(--nord8);
  border-bottom-color: var(--nord8);
}

.accent {
  color: var(--nord8);
  font-weight: 600;
}

.nord-hr {
  margin: 2rem 0;
  border: 0;
  height: 1px;
  background: linear-gradient(to right, transparent, var(--nord3), transparent);
}

.highlight-block {
  text-align: center;
  background: rgba(67, 76, 94, 0.25);
  padding: 1rem;
  border-radius: 20px;
  margin: 1.5rem 0;
  border-left: 3px solid var(--nord8);
  border-right: 3px solid var(--nord8);
}
.big-link {
  font-size: 1.8rem;
  font-weight: bold;
  display: inline-block;
  margin: 0.5rem 0;
}
.big-link a {
  border-bottom: none;
  background: linear-gradient(120deg, var(--nord8), var(--nord7));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 800;
}
.big-link a:hover {
  background: linear-gradient(120deg, var(--nord9), var(--nord6));
  -webkit-background-clip: text;
  background-clip: text;
}
.note {
  font-size: 0.85rem;
  color: var(--nord3);
}

code {
  background: var(--nord1);
  padding: 0.2rem 0.5rem;
  border-radius: 12px;
  font-size: 0.9rem;
  color: var(--nord8);
  margin: 0 2px;
}
.small {
  font-size: 0.8rem;
  color: var(--nord3);
}

img {
  max-width: 100%;
  height: auto;
  vertical-align: middle;
}

.footer-note {
  margin-top: 1rem;
  font-size: 0.8rem;
  color: var(--nord3);
}

@media (max-width: 600px) {
  .nord-wrapper { padding: 1rem; }
  .big-link { font-size: 1.2rem; }
  .highlight-block { padding: 0.8rem; }
}
</style>
