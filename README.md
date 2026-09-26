## Hi there 👋

<!--
**camelsoftt-bykus/camelsoftt-bykus** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# Merhaba, Ben [camelsoftt-bykus] 👋

Şu anda **[çoklu alanlarla çalışan bir ekosistem/ kendisini geliştiren bir şirket]** üzerine projeler geliştiriyorum.

---

### 🛠️ Teknolojiler ve Araçlar
- **Diller:** Python, JavaScript, HTML/CSS
- **Araçlar:** Git, VS Code, Excel, Figma, Claude 

---

### 🚀 Projelerim
- **[Proje Adı 1](link):** Ekosistem.
- **[Proje Adı 2](link):** ai şirket.

---

### 📬 İletişim
- **LinkedIn:** [linkedin.com/in/kullaniciadi](https://linkedin.com)
- **E-posta:** camelsoftt@gmail.com

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)


![GitHub Stats](https://github-readme-stats.vercel.app/api?username=KULLANICI_ADINIZ&show_icons=true&theme=flat)


<h3 align="center">🤖 Arka Plan Ajan Takibi (Agent Monitor)</h3>

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="./assets/dwarf-miner.gif" width="200px" alt="Dwarf Agent"><br>
      <b>Gimli - Mining / Data Processing Agent</b><br>
      <sub>Status: 🟢 Working (Kazı Yapıyor)</sub>
    </td>
    <td align="center" width="50%">
      <img src="./assets/elf-coder.gif" width="200px" alt="Elf Agent"><br>
      <b>Elrond - Coding & Logic Agent</b><br>
      <sub>Status: 🟢 Working (Kod Analizi Yapıyor)</sub>
    </td>
  </tr>
</table>

<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Agent Activity Monitor</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="monitor-container">
    <header class="monitor-header">
      <h1>🛡️ AGENT ACTIVITY MONITOR</h1>
      <p class="subtitle">SYSTEM STATUS: ALL AGENTS ACTIVE</p>
    </header>

    <div class="agent-grid">
      <!-- DWARF AGENTS (Madenciler / Veri İşleyiciler) -->
      <div class="agent-card dwarf-theme">
        <div class="agent-badge">DWARF</div>
        <div class="avatar-box">
          <div class="pixel-avatar dwarf-miner"></div>
        </div>
        <div class="agent-info">
          <h3>Gimli</h3>
          <p class="role">Data Mining & Scraping</p>
          <div class="status-bar"><div class="progress p-85"></div></div>
          <span class="status-text">⛏️ Mining Data... (%85)</span>
        </div>
      </div>

      <div class="agent-card dwarf-theme">
        <div class="agent-badge">DWARF</div>
        <div class="avatar-box">
          <div class="pixel-avatar dwarf-smith"></div>
        </div>
        <div class="agent-info">
          <h3>Durin</h3>
          <p class="role">Resource Gathering</p>
          <div class="status-bar"><div class="progress p-60"></div></div>
          <span class="status-text">🔨 Processing Resources... (%60)</span>
        </div>
      </div>

      <!-- ELF AGENTS (Karmaşık Görevler / Kod / Analiz) -->
      <div class="agent-card elf-theme">
        <div class="agent-badge">ELF</div>
        <div class="avatar-box">
          <div class="pixel-avatar elf-coder"></div>
        </div>
        <div class="agent-info">
          <h3>Elrond</h3>
          <p class="role">Logic & Code Optimization</p>
          <div class="status-bar"><div class="progress p-95"></div></div>
          <span class="status-text">📜 Writing Magic Scripts... (%95)</span>
        </div>
      </div>

      <div class="agent-card elf-theme">
        <div class="agent-badge">ELF</div>
        <div class="avatar-box">
          <div class="pixel-avatar elf-analyst"></div>
        </div>
        <div class="agent-info">
          <h3>Galadriel</h3>
          <p class="role">Strategy & Forecasting</p>
          <div class="status-bar"><div class="progress p-40"></div></div>
          <span class="status-text">✨ Analyzing Future Trends... (%40)</span>
        </div>
      </div>
    </div>
  </div>

</body>
</html>

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
  background-color: #0d1117;
  color: #c9d1d9;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  padding: 20px;
}

.monitor-container {
  width: 100%;
  max-width: 900px;
  background: #161b22;
  border: 1px solid #30363d;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.5);
}

.monitor-header {
  text-align: center;
  margin-bottom: 25px;
  border-bottom: 1px solid #30363d;
  padding-bottom: 15px;
}

.monitor-header h1 {
  font-size: 1.8rem;
  color: #58a6ff;
  letter-spacing: 1px;
}

.subtitle {
  font-size: 0.85rem;
  color: #3fb950;
  margin-top: 5px;
}

.agent-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.agent-card {
  background: #21262d;
  border-radius: 8px;
  padding: 15px;
  position: relative;
  border: 1px solid #30363d;
  transition: transform 0.2s;
}

.agent-card:hover {
  transform: translateY(-5px);
}

.dwarf-theme { border-left: 4px solid #d97706; }
.elf-theme { border-left: 4px solid #10b981; }

.agent-badge {
  position: absolute;
  top: 10px;
  right: 10px;
  font-size: 0.65rem;
  padding: 2px 6px;
  border-radius: 4px;
  font-weight: bold;
}

.dwarf-theme .agent-badge { background: #d97706; color: #fff; }
.elf-theme .agent-badge { background: #10b981; color: #fff; }

.avatar-box {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 70px;
  margin-bottom: 10px;
}

/* KOD YOLUYLA ANİMASYONLU AVATARLAR */
.pixel-avatar {
  width: 45px;
  height: 45px;
  border-radius: 50%;
  animation: pulse-work 1.2s infinite ease-in-out;
}

.dwarf-miner {
  background: #d97706;
  box-shadow: 0 0 15px rgba(217, 119, 6, 0.6);
}

.dwarf-smith {
  background: #b45309;
  box-shadow: 0 0 15px rgba(180, 83, 9, 0.6);
}

.elf-coder {
  background: #10b981;
  box-shadow: 0 0 15px rgba(16, 185, 129, 0.6);
}

.elf-analyst {
  background: #06b6d4;
  box-shadow: 0 0 15px rgba(6, 182, 212, 0.6);
}

@keyframes pulse-work {
  0% { transform: scale(0.95); opacity: 0.8; }
  50% { transform: scale(1.1); opacity: 1; }
  100% { transform: scale(0.95); opacity: 0.8; }
}

.agent-info h3 {
  font-size: 1.1rem;
  color: #f0f6fc;
}

.role {
  font-size: 0.75rem;
  color: #8b949e;
  margin-bottom: 10px;
}

.status-bar {
  background: #30363d;
  height: 6px;
  border-radius: 3px;
  overflow: hidden;
  margin-bottom: 6px;
}

.progress {
  height: 100%;
  background: #3fb950;
  border-radius: 3px;
}

.p-85 { width: 85%; }
.p-60 { width: 60%; }
.p-95 { width: 95%; }
.p-40 { width: 40%; }

.status-text {
  font-size: 0.7rem;
  color: #3fb950;
  display: block;
}
