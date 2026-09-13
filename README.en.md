# Hola Apps (霍拉应用)

> Local-first Windows productivity toolbox · **29 tools** (12 free + 17 membership) · runs offline by default, data stays on your machine

中文版本：[`README.md`](./README.md)

## About

Hola Apps is a local-first collection of productivity tools for Windows, covering clipboard, capture, files, system, network and translation. It is hotkey and global-search driven, tray-resident and always ready, install-and-go, open-and-use — and **the vast majority of tools work fully offline**.

**Official website**: [https://www.apphola.com/](https://www.apphola.com/)

**This repository publishes production builds only** (see [Releases](https://github.com/apphola-com/apphola/releases)) — no source code.

---

## 📸 Screenshots

> Screenshots live in the [`screenshots/`](./screenshots/) folder. Place the images with the following filenames there (replace with real screenshots before publishing; images are illustrative).

![Home · Tools overview](screenshots/home.png)
<p align="center"><em>Home · overview of 29 tools</em></p>

![Sample tool panel](screenshots/panel.png)
<p align="center"><em>An example tool operation panel</em></p>

![Membership sign-in & unlock](screenshots/member.png)
<p align="center"><em>Membership sign-in and feature unlock</em></p>

---

## ✨ Features

29 tools across six categories (★ = membership-exclusive, unlocked after signing in):

### Input
- Super Clipboard
- Text Snippets (code snippets)
- Sticky Notes
- ★ Text Toolbox
- ★ Regex Tester
- ★ Text / File Diff

### Capture
- Screenshot & Sticker
- Quick Look (images / PDF / code / archives)
- Screen Color Picker
- ★ Offline OCR

### Window
- Hotkey Manager
- System Monitor
- ★ System Report
- ★ Mouse Spotlight / Highlight
- ★ Pomodoro / Focus Timer

### File
- File Hash Check
- ★ Batch Rename
- ★ Image Compress / Convert
- ★ Duplicate File Finder
- ★ Privacy Cleaner / File Shredder
- ★ Scheduled Command Runner
- ★ File Encrypt / Decrypt (AES-256)
- ★ Scheduled Backup / Sync

### Network
- Scheduled Tasks
- ★ LAN Transfer (never leaves your network)
- ★ QR Code Generator
- ★ Network Port Scan

### AI & Translation
- AI Translate (requires an AI model config)
- Machine Translation (requires an Alibaba Cloud AccessKey; 214 languages)

---

## ⚙️ Global Configuration Center

Fill it in once and every tool shares it — no need to re-enter keys per tool:

- **Alibaba Cloud OSS**: Endpoint, Bucket, Region, AccessKey, etc.
- **Alibaba Cloud AccessKey**: AccessKey ID + AccessKey Secret (used by Machine Translation)
- **AI Model**: Base URL, API Key, model (**OpenAI-compatible**)

---

## 🌐 Languages

The interface ships in **13 languages**: 简体中文, English, 日本語, 한국어, Deutsch, Français, Español, Português, Русский, العربية, हिन्दी, বাংলা, اردو.

---

## 🚀 Download & Install

1. Open the [Releases](https://github.com/apphola-com/apphola/releases) page.
2. Download the latest installer (`*.exe` or `*.msi`).
3. Run the installer; the WebView2 runtime will be bootstrapped automatically on first launch if needed.

> Installers are **production (Release) builds** containing only the final artifacts.

---

## 🖥 System Requirements

- **OS**: Windows 10 (1703+) or Windows 11
- **Architecture**: x64
- **Runtime**: Microsoft Edge WebView2 (auto-installed)

---

## 🔐 Membership

- Free users get **12 core tools**.
- Tools marked **★ membership-exclusive** unlock after you **sign in and have an active membership**.
- Get a membership: visit the official subscription page [https://www.apphola.com/zh-CN/pricing](https://www.apphola.com/zh-CN/pricing).
- Membership status is verified locally and works offline; account/membership data stays on your own machine.

---

## 🔒 Privacy & Local-first

- **Local-first**: the vast majority of tools run fully offline (clipboard, screenshot, color picker, OCR, hash check, file encryption, batch rename, image tools, privacy cleaner, backup, and more). Data is kept on your machine by default.
- **Only three features require a network connection**, and each uses **your own account and keys** — nothing is sent if you don't configure them:
  - Membership sign-in and subscription
  - AI Translate (OpenAI-compatible endpoint)
  - Machine Translation (Alibaba Cloud Machine Translation)
- Outside of those, the app never uploads your data automatically.

---

## Support

Submit issues or suggestions via [Issues](https://github.com/apphola-com/apphola/issues).
