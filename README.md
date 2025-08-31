### 🤖 REDTECHXMD v1.0

**REDTECH XMD** is a powerful multi-device WhatsApp bot built using the [Baileys](https://github.com/WhiskeySockets/Baileys) library. It helps group admins manage members, automate tasks, and enhance engagement with fun and useful features.

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Ribeye&size=50&pause=1000&color=33ff00&center=true&width=910&height=100&lines=REDTECHXMD;Multi+Device+Whatsapp+Bot;Coded+By+DEVTUNTU" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <a href="https://youtube.com/@redtech">
    <img src="https://files.catbox.moe/urvr8a.jpg" alt="REDTECHXMD" height="300">
  </a>
</div>

---

## 🚀 Deploy Options

### 🔹 Fork the Repository

<div align="center">
  <a href="https://github.com/devtuntu474">
    <img src="https://img.shields.io/badge/Fork-Repository-blue?style=for-the-badge" alt="Fork the repository"/>
  </a>
</div>

### 🔹 Deploy Now

For further customization and setup guidance, click the button below:

<div align="center">
  <a href="Sorry for not responding">
    <img src="https://img.shields.io/badge/Deploy Tutorial-dc3545?style=for-the-badge&logo=youtube" alt="YouTube Link"/>
  </a>
  <a href="https://bot-hosting.net/?aff=1373032148830916668">
    <img src="https://img.shields.io/badge/Deploy on Panel-28a745?style=for-the-badge" alt="Deploy on Panel"/>
  </a>
</div>


### Deploy Now on Below Panel
<div align="center">
<a href="https://dashboard.katabump.com/auth/login#28e446" target="_blank">
  <img src="https://img.shields.io/badge/Katabump-D6B7D6?style=for-the-badge&logo=server&logoColor=black" alt="Katabump"/>
</a>
</div>

---

## 🛠️ Installation & Setup

### Prerequisites

- Node.js (v20.x recommended)
- Git installed

### Step-by-Step Setup

```bash
# Clone the repository
git clone https://github.com/devtuntu474
cd REDTECH XMD

# Install dependencies
npm install

# Start the bot
node index.js
```

> ✅ Once the bot starts, scan the QR code shown in the terminal using WhatsApp's Linked Devices feature.

---

*⚙️ GitHub Workflow (CI/CD)*

```yaml
name: Node.js CI

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
      - name: Checkout repository
        uses: actions/checkout@v3

      - name: Set up Node.js
        uses: actions/setup-node@v3
        with:
          node-version: ${{ matrix.node-version}}

      - name: Install dependencies
        run: npm install

      - name: Start application
        run: npm start
```

---

*🤩 Features*

- 🔔 Tag all group members with `.tagall`
- 🔒 Admin-only command access
- 🎮 Group games like Tic-Tac-Toe
- 🔊 Text-to-Speech with `.tts`
- 🖼️ Sticker creation with `.sticker`
- 🚫 Anti-link detection
- ⚠️ Warn and manage group members
- 📌 Multi-device support via Baileys

---

*📚 License & Credits*

This project uses open-source libraries including:

- [Baileys](https://github.com/WhiskeySockets/Baileys) (MIT License)
- Other dependencies listed in `package.json`

---

*👥 Join the Community*

<div align="center">
  <a href="https://t.me/+LwD1jbJ4qmRlYjJk">
    <img src="https://img.shields.io/badge/Join%20Telegram-0078E7?style=for-the-badge&logo=telegram&logoColor=white" alt="Join Telegram"/>
  </a>
  <a href="https://whatsapp.com/channel/0029VbBGQu4C6ZvnH201CL0o">
    <img src="https://img.shields.io/badge/Join%20WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Join WhatsApp"/>
  </a>
</div>

---

> 💡 Feel free to contribute, report issues, or suggest new features. Let's build something awesome together!
