# ◈ RayHunter Install Wizard

> **Interactive step-by-step guide to flash [EFF's Rayhunter](https://github.com/EFForg/rayhunter) IMSI catcher detector on an Orbic RC400L hotspot from Windows.**

[![GitHub Pages](https://img.shields.io/badge/Launch-Install%20Wizard-00ff88?style=for-the-badge&logo=github)](https://YOUR_USERNAME.github.io/rayhunter-install-wizard/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 🚀 Launch the Wizard

**👉 [Open the Install Wizard](https://YOUR_USERNAME.github.io/rayhunter-install-wizard/)**

Replace `YOUR_USERNAME` with your GitHub username after deployment.

---

## What is Rayhunter?

[Rayhunter](https://github.com/EFForg/rayhunter) is the Electronic Frontier Foundation's open-source tool for detecting IMSI catchers (cell-site simulators / stingrays). It runs on an inexpensive Orbic RC400L mobile hotspot (~$15–30 USD) and monitors cellular traffic for signs of surveillance.

This wizard provides a guided, beginner-friendly installation experience specifically for **Windows** users.

## Features

- **8-step interactive wizard** with progress tracking
- **WiFi & USB install methods** — toggle between both with method-specific instructions
- **Copy-to-clipboard commands** — one-click copy for all PowerShell commands
- **Interactive checklists** — track your progress through each step
- **Troubleshooting FAQ** — accordion-style answers for common issues
- **Fully offline** — runs as a single HTML file, no build step or dependencies
- **Mobile-friendly** — responsive design works on phones and tablets
- **Dark theme** — easy on the eyes

## Quick Start

### Option 1: Use GitHub Pages (recommended)

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → `main` → `/ (root)`**
4. Your wizard is live at `https://YOUR_USERNAME.github.io/rayhunter-install-wizard/`

### Option 2: Open locally

Just double-click `index.html` — it's a single self-contained file with no dependencies.

## What You'll Need

| Item | Details |
|---|---|
| **Orbic RC400L** | ~$15–30 on eBay/Amazon. Kajeet RC400L also works. |
| **SIM card** | Any SIM — does not need an active plan. |
| **Windows 10/11** | With PowerShell available. |
| **WiFi or USB-C cable** | WiFi method recommended (no driver setup). |

## Project Structure

```
rayhunter-install-wizard/
├── index.html          # The complete wizard app (single file)
├── README.md           # This file
├── LICENSE             # MIT License
└── .nojekyll           # Tells GitHub Pages to skip Jekyll processing
```

## Disclaimer

This is an **unofficial** companion guide. Rayhunter is developed by the [Electronic Frontier Foundation](https://www.eff.org/) under GPLv3. This wizard does not modify, redistribute, or bundle any Rayhunter software — it only provides installation instructions that link to official EFF releases.

**Legal:** Use Rayhunter at your own risk. EFF believes running this program does not currently violate any laws or regulations in the United States. Check your local laws.

## Links

- [Rayhunter GitHub](https://github.com/EFForg/rayhunter)
- [Rayhunter Documentation](https://efforg.github.io/rayhunter/)
- [EFF Blog Post](https://www.eff.org/deeplinks/2025/03/introducing-rayhunter)
- [Official Releases](https://github.com/EFForg/rayhunter/releases)

## License

This wizard is released under the [MIT License](LICENSE). Rayhunter itself is licensed under GPLv3 by the EFF.
