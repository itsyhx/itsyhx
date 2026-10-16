<div align="center">
  <h1>👋 Hi, I'm Harrison Yin</h1>
  <p><b>Security Researcher — 网络安全研究员 / 白帽子</b></p>

  <p>
    <a href="https://github.com/itsyhx">
      <img src="https://img.shields.io/badge/GitHub-itsyhx-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="https://github.com/itsyhx?tab=repositories">
      <img src="https://img.shields.io/badge/SRC%20Hunter-漏洞挖掘-critical?style=for-the-badge&logo=shield&logoColor=white" alt="SRC Hunter" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=itsyhx&color=brightgreen&style=for-the-badge&label=Profile%20Views" alt="Views" />
  </p>

  <p>
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=00E676&center=true&vCenter=true&width=620&lines=Breaking%20access%20control%2C%20legally.;黑盒%20SRC%20%2B%20白盒%20代码审计;Turning%20one%20IDOR%20into%20a%20full%20chain." alt="Typing SVG" />
  </p>
</div>

---

## 🛡️ 关于我 / About Me

<div align="center">

| 🎯 | **方向** | 黑盒 SRC 挖洞 · 白盒 0day 审计 · 业务逻辑漏洞 |
|:--:|:---|:---|
| 🔍 | **擅长** | 越权/IDOR · 注入 · SSRF · XSS · 认证绕过 · 漏洞链串联 |
| 🧰 | **工具** | Burp Suite · Frida · IDA/Ghidra · 自研 Python 工具链 |
| 📋 | **原则** | 不堆叠低危、不误报、每个洞必须可复现 |

</div>

**我理解的挖洞：** 不是扫出一个 200 就交报告，而是理解业务逻辑和代码意图，找到开发者的认知盲区 —— 那些"以为做了鉴权但其实没有"的地方。

---

## 🔥 近期研究 / Recent Work

| 成果 | 说明 |
|------|------|
| 🏫 [smart-campus-authz-audit](https://github.com/itsyhx/smart-campus-authz-audit) | **智慧校园平台越权漏洞完整审计** — JWT `menuPermission: ["*:*:*"]` 通配授导致学生账号可读全校敏感数据；含脱敏数据集、PoC 工具链、自查脚本方法论 |

**该项目的核心发现：**
- SSO 签发 JWT 权限声明通配 → **平台级鉴权配置缺陷**，与账号来源无关
- 4 个不同学生账号权限完全一致 → `userId` 正负号存在两套命名空间，不能作为账号类型判据
- 实际放行：教职工名录(746条含手机号)、请假事由、住宿记录、校长信箱全文、导出链接
- **自查工具自身的正则黑名单有 10+ 写动词漏判** — 报告里如实披露了这个"不安全的自我承诺"

---

## 🧰 技能栈 / Tech Stack

<div align="center">

**🔓 Offensive / 攻击面**
<p>
  <img src="https://img.shields.io/badge/IDOR%20%2F%20越权-FF0000?style=flat-square&logo=bug&logoColor=white" alt="IDOR" />
  <img src="https://img.shields.io/badge/SQLi-EA3223?style=flat-square&logo=databricks&logoColor=white" alt="SQLi" />
  <img src="https://img.shields.io/badge/SSRF-F47B20?style=flat-square&logo=nginx&logoColor=white" alt="SSRF" />
  <img src="https://img.shields.io/badge/XSS-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="XSS" />
  <img src="https://img.shields.io/badge/Auth%20Bypass-DC143C?style=flat-square&logo=key&logoColor=white" alt="AuthBypass" />
  <img src="https://img.shields.io/badge/RCE-8B0000?style=flat-square&logo=terminal&logoColor=white" alt="RCE" />
</p>

**🛠️ Tools / 工具**
<p>
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Frida-EF645C?style=flat-square&logo=frida&logoColor=white" alt="Frida" />
  <img src="https://img.shields.io/badge/Ghidra-5AC8ED?style=flat-square&logo=apache&logoColor=white" alt="Ghidra" />
  <img src="https://img.shields.io/badge/nuclei-00C7B7?style=flat-square&logo=nuclei&logoColor=white" alt="nuclei" />
  <img src="https://img.shields.io/badge/JS%20Reverse-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS" />
</p>

**📚 Knowledge / 知识域**
<p>
  <img src="https://img.shields.io/badge/OWASP%20Top%2010-1F425F?style=flat-square&logo=owasp&logoColor=white" alt="OWASP" />
  <img src="https://img.shields.io/badge/业务逻辑-5A2CA0?style=flat-square&logo=gitgraph&logoColor=white" alt="Logic" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

</div>

---

## 📊 GitHub 数据 / Stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=itsyhx&show_icons=true&theme=midnight-purple&hide_border=true&count_private=true&include_all_commits=true" alt="Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=itsyhx&layout=compact&theme=midnight-purple&hide_border=true&langs_count=8" alt="Top Langs" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=itsyhx&theme=midnight-purple&hide_border=true&locale=en&date_format=M%20j%5B%20S%5D" alt="Streak" />
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=itsyhx&theme=darkhub&no-frame=true&row=1&column=7&margin-w=8" alt="Trophy" />
</div>

---

## 🐍 贡献贪吃蛇 / Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itsyhx/itsyhx/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/itsyhx/itsyhx/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution Snake" src="https://raw.githubusercontent.com/itsyhx/itsyhx/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=100&section=footer&text=Stay%20Curious%20·%20Stay%20Ethical&fontSize=20&fontAlignY=60&animation=fadeIn&descAlignY=70&descAlign=50" alt="footer" />
  <p><sub>技术若有害则用之有度，若有利则用之无尽 · Authorized research only</sub></p>
</div>
