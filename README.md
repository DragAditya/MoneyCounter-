<!-- HEADER BANNER -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=MoneyCounter&fontSize=60&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Premium%20Indian%20Note%20Counter%20%C2%B7%20Bundle%20%C2%B7%20Calculator&descAlignY=60&descColor=ffffff99" width="100%"/>

<br/>

[![PWA](https://img.shields.io/badge/PWA-Ready-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://github.com/yourusername/MoneyCounter)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/yourusername/MoneyCounter)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/yourusername/MoneyCounter)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/yourusername/MoneyCounter)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Offline](https://img.shields.io/badge/Works-Offline-brightgreen?style=for-the-badge&logo=cloudflare&logoColor=white)](https://github.com/yourusername/MoneyCounter)

<br/>

[![Stars](https://img.shields.io/github/stars/yourusername/MoneyCounter?style=social)](https://github.com/yourusername/MoneyCounter/stargazers)
[![Forks](https://img.shields.io/github/forks/yourusername/MoneyCounter?style=social)](https://github.com/yourusername/MoneyCounter/network/members)
[![Issues](https://img.shields.io/github/issues/yourusername/MoneyCounter?color=red)](https://github.com/yourusername/MoneyCounter/issues)
[![Last Commit](https://img.shields.io/github/last-commit/yourusername/MoneyCounter)](https://github.com/yourusername/MoneyCounter/commits)

<br/>

> **₹ MoneyCounter** — A zero-dependency, fully offline-capable **Progressive Web App** for counting Indian currency notes, building custom money bundles, and performing calculations. Designed with Apple-grade minimalism and four switchable themes. No backend. No login. No tracking. Just money counting — done right.

<br/>

**[🚀 Live Demo](https://moneycounter.netlify.app) · [📱 Install as App](#-installation) · [🐛 Report Bug](https://github.com/yourusername/MoneyCounter/issues) · [✨ Request Feature](https://github.com/yourusername/MoneyCounter/issues)**

<br/>

</div>

---

<!-- SCREENSHOT / PREVIEW -->
## 📸 Preview

<div align="center">

| Light | Dark | Warm | Slate |
|:---:|:---:|:---:|:---:|
| ![Light Theme](https://via.placeholder.com/180x360/f5f3f0/18160f?text=Light) | ![Dark Theme](https://via.placeholder.com/180x360/0c0c0c/eeeae3?text=Dark) | ![Warm Theme](https://via.placeholder.com/180x360/fdf6ec/b86820?text=Warm) | ![Slate Theme](https://via.placeholder.com/180x360/edf0f6/1d4ed8?text=Slate) |

</div>

---

<!-- TABLE OF CONTENTS -->
## 📋 Table of Contents

<details>
<summary>Click to expand</summary>

- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [📱 Installation](#-installation)
- [🚀 Deploy](#-deploy)
- [🏗 Project Structure](#-project-structure)
- [🎨 Themes](#-themes)
- [📦 Sections](#-sections)
- [⚡ PWA Capabilities](#-pwa-capabilities)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [💬 Acknowledgements](#-acknowledgements)

</details>

---

## ✨ Features

<table>
<tr>
<td>

### 💵 Note Counter
- Count ₹500, ₹200, ₹100, ₹50, ₹20, ₹10
- Direct keyboard input — no + / − buttons
- Live subtotal per denomination
- Additional field for coins & loose change
- Real-time amount-in-words (Indian system)
- Session save & history with timestamps

</td>
<td>

### 📦 Bundle Calculator
- Add unlimited custom money bundles
- E.g. ₹45,000 + ₹80,000 + ₹1,20,000
- Live grand total + average + largest entry
- One-tap copy formatted summary
- Persistent across tab switches

</td>
</tr>
<tr>
<td>

### ⌗ Calculator
- Apple-style layout, 4-column grid
- Full expression trail display
- Rupee words shown for result
- Keyboard shortcut support
- Copy result in one tap

</td>
<td>

### 🎨 Design & UX
- 4 premium themes: Light · Dark · Warm · Slate
- Smooth directional page transitions
- Zero data loss when switching tabs
- `localStorage` persistence across sessions
- Works 100% offline after first load

</td>
</tr>
</table>

---

## 🛠 Tech Stack

<div align="center">

| Layer | Technology |
|---|---|
| **Markup** | HTML5 semantic structure |
| **Styling** | Pure CSS3 — Variables, Grid, Flexbox, Animations |
| **Logic** | Vanilla JavaScript ES6+ — zero dependencies |
| **Fonts** | Google Fonts — Instrument Serif + Geist |
| **Offline** | Service Worker (Cache-first strategy) |
| **Install** | Web App Manifest (PWA spec) |
| **Storage** | `localStorage` — fully client-side, private |
| **Icons** | PNG (192×192 + 512×512) |
| **Deploy** | Netlify / GitHub Pages / any static host |

</div>

> 🔒 **No frameworks. No npm. No build step. No data collection.** Drop the files and it works.

---

## 📱 Installation

### Install as App (Recommended)

#### Android (Chrome)
```
1. Open the live URL in Chrome
2. Tap ⋮  (three dots) in the top right
3. Tap "Add to Home Screen"
4. Tap "Install"
```

#### iPhone / iPad (Safari)
```
1. Open the live URL in Safari
2. Tap the Share button (□↑)
3. Scroll down → tap "Add to Home Screen"
4. Tap "Add"
```

> ✅ Once installed: full-screen, no browser bar, works offline, app icon on home screen.

---

### Run Locally

**No install required — just open the file:**

```bash
# Clone the repo
git clone https://github.com/yourusername/MoneyCounter.git
cd MoneyCounter

# Option 1: Open directly in browser
open index.html

# Option 2: Serve locally (needed for SW + PWA features)
npx serve .
# → http://localhost:3000

# Option 3: Python simple server
python3 -m http.server 8080
# → http://localhost:8080
```

> ⚠️ Service Workers require HTTPS or `localhost`. For full PWA testing, use `npx serve` or deploy.

---

## 🚀 Deploy

### ▲ Netlify (Recommended — 2 minutes)

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login
netlify login

# Deploy
cd MoneyCounter
netlify deploy --prod --dir .
```

Or drag-and-drop the folder at **[app.netlify.com](https://app.netlify.com)**.

---

### 🐙 GitHub Pages

```bash
# Push to GitHub
git init
git add .
git commit -m "feat: initial MoneyCounter release"
git remote add origin https://github.com/yourusername/MoneyCounter.git
git push -u origin main

# Enable Pages:
# GitHub repo → Settings → Pages → Source: main / root
```

Live at: `https://yourusername.github.io/MoneyCounter`

---

### 🌐 Google Play Store (via Bubblewrap)

```bash
# Install Bubblewrap
npm install -g @bubblewrap/cli

# Initialize TWA from your live manifest
bubblewrap init --manifest https://your-url/manifest.json

# Build APK
bubblewrap build

# Output: app-release-signed.apk → ready for Play Store upload
```

---

## 🏗 Project Structure

```
MoneyCounter/
│
├── 📄 index.html          # Entire app — HTML + CSS + JS (single file)
├── 📋 manifest.json       # PWA manifest — name, icons, theme, shortcuts
├── ⚙️  sw.js               # Service Worker — offline cache strategy
├── 🖼  icon-192.png        # App icon for Android / Chrome
├── 🖼  icon-512.png        # App icon for splash screens
└── 📖 README.md           # You are here
```

> **Why single file?** Zero build complexity, instant deployment, easy to fork and self-host. The entire app is ~870 lines of clean, commented code.

---

## 🎨 Themes

MoneyCounter ships with **4 hand-crafted themes**, each with its own complete color palette:

| Theme | Background | Accent | Style |
|:---:|:---:|:---:|:---|
| ☀️ **Light** | `#f5f3f0` | `#18160f` | Warm off-white, classic minimal |
| 🌙 **Dark** | `#0c0c0c` | `#eeeae3` | Pure dark, cream text |
| 🟠 **Warm** | `#fdf6ec` | `#b86820` | Amber gold, earthy tones |
| 🔵 **Slate** | `#edf0f6` | `#1d4ed8` | Cool blue-grey, professional |

All themes apply across all 3 sections simultaneously and are persisted in `localStorage`.

---

## 📦 Sections

### 1. ₹ Note Counter

Count Indian currency denominations with real-time totals:

```
₹500 × 12  =  ₹6,000
₹200 ×  5  =  ₹1,000
₹100 ×  8  =  ₹800
₹50  ×  4  =  ₹200
₹20  ×  3  =  ₹60
₹10  × 10  =  ₹100
Additional  =  ₹50
─────────────────────
Total       =  ₹8,210

"Eight Thousand Two Hundred Ten Rupees Only"
```

---

### 2. 📦 Bundle

Add any custom amounts and see a running total:

```
1. ₹ 45,000
2. ₹ 80,000
3. ₹ 1,20,000
──────────────
Total  ₹2,45,000
Avg    ₹81,667
Max    ₹1,20,000
```

---

### 3. ⌗ Calculator

Standard Apple-layout calculator with INR-formatted output and amount-in-words.

---

## ⚡ PWA Capabilities

| Feature | Status |
|---|:---:|
| Installable (Add to Home Screen) | ✅ |
| Offline support | ✅ |
| App shortcuts (long-press icon) | ✅ |
| Theme-color sync with OS | ✅ |
| Splash screen | ✅ |
| No browser navigation bar | ✅ |
| Portrait orientation lock | ✅ |
| localStorage data persistence | ✅ |
| Service Worker (cache-first) | ✅ |
| Play Store via Bubblewrap TWA | ✅ |

---

## 🗺 Roadmap

```
v1.0  ✅  Note Counter + Bundle + Calculator
v1.1  🔲  Session export as PDF / CSV
v1.2  🔲  Daily summary view
v1.3  🔲  Split calculator (divide total ÷ people)
v1.4  🔲  Target mode (how much more to reach goal)
v1.5  🔲  Haptic feedback (mobile vibration API)
v2.0  🔲  Google Drive sync (optional)
v2.1  🔲  Multi-language support (Hindi, Tamil, etc.)
v2.2  🔲  Play Store listing
```

Want a feature? [Open an issue →](https://github.com/yourusername/MoneyCounter/issues/new?template=feature_request.md)

---

## 🤝 Contributing

Contributions are welcome! MoneyCounter is intentionally **zero-dependency** — please keep PRs framework-free.

```bash
# 1. Fork the repo
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/MoneyCounter.git

# 3. Create a feature branch
git checkout -b feat/your-feature-name

# 4. Make your changes to index.html / sw.js / manifest.json

# 5. Test locally
npx serve .

# 6. Commit with conventional commits
git commit -m "feat: add split calculator"

# 7. Push and open a Pull Request
git push origin feat/your-feature-name
```

### Commit Convention

| Prefix | Use for |
|---|---|
| `feat:` | New feature |
| `fix:` | Bug fix |
| `style:` | CSS/UI changes |
| `perf:` | Performance improvement |
| `docs:` | Documentation |
| `chore:` | Maintenance |

---

## 📄 License

```
MIT License

Copyright (c) 2025 MoneyCounter

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.
```

See [LICENSE](LICENSE) for full text.

---

## 💬 Acknowledgements

- **[Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif)** — Display typeface by Rodrigo Fuenzalida
- **[Geist](https://vercel.com/font)** — Interface font by Vercel
- **[Shields.io](https://shields.io)** — Badge generation
- **[Capsule Render](https://github.com/kyechan99/capsule-render)** — Header banner
- Inspired by the simplicity of Apple's native Calculator app

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

**Made with ♥ for India's cash economy**

⭐ Star this repo if MoneyCounter saved you time counting notes!

[![GitHub stars](https://img.shields.io/github/stars/yourusername/MoneyCounter?style=social)](https://github.com/yourusername/MoneyCounter)

</div>
