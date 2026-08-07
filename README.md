<div align="center">

# 🖤 AURA — WhatsApp Bot

**⛧ The dark has awakened. Speak, and Aura listens. ⛧**

[![npm version](https://img.shields.io/npm/v/@astralcore/aura-wb?color=8A2BE2&label=npm)](https://www.npmjs.com/package/@astralcore/aura-wb)
[![npm downloads](https://img.shields.io/npm/dt/@astralcore/aura-wb?color=8A2BE2)](https://www.npmjs.com/package/@astralcore/aura-wb)
[![License](https://img.shields.io/badge/license-MIT-8A2BE2)](#)

*One command. Zero prompts. Bot online.*

</div>

---

## ⚡ Install

Pick your platform, paste the **one line**, press enter. No prompts, no confirmations — everything runs fully non-interactively from start to finish.

### 📱 Termux (Android)

```bash
DEBIAN_FRONTEND=noninteractive pkg update -y -o Dpkg::Options::="--force-confdef" -o Dpkg::Options::="--force-confold" && DEBIAN_FRONTEND=noninteractive pkg upgrade -y -o Dpkg::Options::="--force-confdef" -o Dpkg::Options::="--force-confold" && pkg install -y nodejs-lts git python which termux-api && termux-setup-storage && npm install -g @astralcore/aura-wb && aura-wb
```

> 📦 Storage permission popup will appear once — tap **Allow**. That's the only manual step, ever.

### 🐧 Ubuntu / Debian (VPS)

```bash
sudo DEBIAN_FRONTEND=noninteractive apt-get update -y -o Dpkg::Options::="--force-confdef" -o Dpkg::Options::="--force-confold" && sudo DEBIAN_FRONTEND=noninteractive apt-get upgrade -y -o Dpkg::Options::="--force-confdef" -o Dpkg::Options::="--force-confold" && sudo DEBIAN_FRONTEND=noninteractive apt-get install -y -o Dpkg::Options::="--force-confdef" -o Dpkg::Options::="--force-confold" nodejs npm git python3 build-essential && sudo npm install -g @astralcore/aura-wb && aura-wb
```

### 🎩 CentOS / Fedora / RHEL (VPS)

```bash
sudo dnf update -y -q && sudo dnf install -y -q nodejs npm git python3 gcc-c++ make && sudo npm install -g @astralcore/aura-wb && aura-wb
```

### 🏔️ Alpine (Docker containers)

```bash
apk update -q && apk add --no-cache -q nodejs npm git python3 build-base && npm install -g @astralcore/aura-wb && aura-wb
```

### 🍎 macOS

```bash
NONINTERACTIVE=1 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" && NONINTERACTIVE=1 brew install node git && npm install -g @astralcore/aura-wb && aura-wb
```

> 🔧 If this is a brand-new Mac, macOS may pop up a one-time GUI dialog to install Xcode Command Line Tools — that's an Apple system dialog, not something any script can skip. Click **Install** if it appears.

### 🪟 Windows (PowerShell — run as Administrator)

```powershell
$ProgressPreference='SilentlyContinue'; winget install -e --id OpenJS.NodeJS.LTS --accept-package-agreements --accept-source-agreements --silent; winget install -e --id Git.Git --accept-package-agreements --accept-source-agreements --silent; npm install -g @astralcore/aura-wb; aura-wb
```

---

## 🔄 Restart the bot

Session data is saved automatically — no need to pair again.

```bash
aura-wb
```

---

## 📞 Contact

Need help, custom setup, or found a bug?

**Telegram:** [t.me/nmd_coder](https://t.me/nmd_coder)

---

<div align="center">

*❪❪ SL AURA ❫❫ | ® ASTRAL CORE*

</div>
