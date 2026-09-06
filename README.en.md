# Hola Apps (霍拉应用)

> Local-first Windows productivity toolbox · **27 tools** · all data stays on your device, never uploaded

中文版本：[`README.md`](./README.md)

## About

Hola Apps is a collection of pure-local productivity tools for Windows, focused on five areas: input, capture, files, system, and network. It is command-palette and hotkey driven, tray-resident and always ready, install-and-go, open-and-use, and works **fully offline**.

**This repository publishes production builds only** (see [Releases](https://github.com/apphola-com/apphola/releases)) — no source code.

---

## 📸 Screenshots

> Screenshots live in the [`screenshots/`](./screenshots/) folder. Place the images with the following filenames there (replace with real screenshots before publishing; images are illustrative).

![Home · Tools overview](screenshots/home.png)
<p align="center"><em>Home · overview of 27 tools</em></p>

![Sample tool panel](screenshots/panel.png)
<p align="center"><em>An example tool operation panel</em></p>

![Membership sign-in & unlock](screenshots/member.png)
<p align="center"><em>Membership sign-in and feature unlock</em></p>

---

## ✨ Features

27 tools across five categories (★ = membership-exclusive, unlocked after signing in):

### Input
- Clipboard history
- Code snippets
- Sticky notes
- ★ Text toolbox
- ★ Regex tester
- ★ Text diff

### Capture
- Screenshot & annotate
- Quick look
- Color picker
- ★ OCR text recognition

### Window
- Global hotkeys
- System monitor
- System report
- Spotlight launcher
- ★ Pomodoro

### File
- Hash check
- ★ Batch rename
- ★ Image toolbox
- ★ Duplicate finder
- ★ Privacy cleaner
- ★ Automation
- ★ File encryption
- ★ Backup

### Network
- Scheduler
- ★ LAN transfer
- ★ QR code generator
- ★ Port scanner

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

- Free users get all core tools.
- Tools marked **★ membership-exclusive** unlock after you **sign in and have an active membership**.
- Membership status is verified locally and works offline; account/membership data stays on your own machine.

---

## 🔒 Privacy & Local-first

- All tools run locally; core features work **without an internet connection**.
- Your data (clipboard, notes, settings, etc.) is stored only on your device and is **never uploaded**.

---

## 🛠 Tech Stack

- **Frontend**: React 19 + TypeScript + Vite + Bootstrap
- **Backend**: Rust + Tauri 2 + SQLite (local storage)
- **i18n**: 13 UI languages

---

## 📦 Release Notes

This repository **publishes production builds only**. Release flow:

1. Build the production artifacts:
   ```bash
   yarn install
   yarn tauri build
   ```
2. Artifacts:
   - MSI: `src-tauri/target/release/bundle/msi/*.msi`
   - NSIS: `src-tauri/target/release/bundle/nsis/*.exe`
3. Create a new tagged release in [Releases](https://github.com/apphola-com/apphola/releases), upload the installers, and write the release notes (you may use [`Tool-Description.en.md`](./Tool-Description.en.md)).

> To use this README as the GitHub repository homepage, copy it to the repository root.

---

## Support

Submit issues or suggestions via [Issues](https://github.com/apphola-com/apphola/issues).