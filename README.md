# 🐧 Methos Linux

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/273648055?s=400&u=fbb9142bb971b858eb47802eccb20fd7c0f7a7cc&v=4" width="180"/>
</p>

<p align="center">
  <b>Arch-based Linux distribution for Developers, AI Engineers & Security Researchers</b>
</p>

<p align="center">
  ⚡ Fast • 🧠 Smart • 🔧 Customizable • 🚀 Online Installer • 🐧 Arch Powered
</p>

---

## 📌 Overview

**Methos Linux** is a custom Arch Linux-based distribution designed to provide a **ready-to-use environment** for:

- 👨‍💻 Developers
- 🤖 AI Engineers / ML Researchers
- 🔐 Security & Pentesting Professionals
- ⚙️ DevOps Engineers

It is built on top of **Arch Linux + Calamares Installer + Pacman ecosystem**, with a focus on:

- Automated online installation
- Profile-based system setup
- Minimal user configuration after installation
- High performance & modular design

---

## 🏗️ Architecture


Arch Linux Base
│
▼
Calamares Installer (Customized)
│
├── Profile System (Developer / AI / DevOps / Pentester)
├── Online Package Installer (Pacman)
├── Conflict Resolver Engine
└── Bootloader (GRUB only)
│
▼
Installed Methos System


---

## ⚙️ Key Features

### 🚀 Smart Installer
- Fully automated **Calamares-based installation**
- Online package installation (latest Arch repositories)
- No offline outdated packages

### 🧠 Profile-Based System
Choose your environment during installation:

- 💻 Developer Profile
- 🤖 AI Engineer Profile
- 🔐 Pentester Profile
- ⚙️ DevOps Profile
- 🎓 Student Profile
- 🪶 Minimal Profile

Each profile installs optimized toolsets automatically.

---

### 📦 Package System
- Powered by `pacman`
- Only official repositories:
  - `core`
  - `extra`
  - `community`
  - `multilib`

❌ No AUR in Alpha (for stability)

---

### 🔄 Smart Conflict Resolution
- Rule-based package conflict handling
- Safe fallback replacements
- Deduplication engine
- Deterministic installation order

---

### 🖥️ Boot System
- GRUB only (BIOS + UEFI unified)
- Simplified boot architecture
- Faster ISO boot process

---

### ⚡ Performance Focus
- Minimal overhead design
- Clean system startup
- Optimized for modern hardware

---

## 📁 Project Structure


methos-linux/
├── archiso/ # ISO build system
├── calamares/ # Installer configuration
├── profiles/ # Package profiles
├── scripts/ # Build & automation tools
├── branding/ # UI themes & assets
├── docs/ # Documentation
└── tests/ # Validation scripts


---

## 🔧 Installation Concept

1. Boot from ISO
2. Launch Calamares Installer
3. Choose your Profile
4. Automatic online installation starts
5. System is configured & ready to use

---

## 🎯 Goals

- 🧩 Simple Arch-based distribution for everyone
- ⚡ Fast installation with latest packages
- 🛠️ Developer-ready environment out of the box
- 🔐 Secure and stable base system
- 📦 Modular profile-based customization

---

## ⚠️ Alpha Status

This project is currently in **Alpha stage**:

- Features are under active development
- Some modules may change frequently
- Stability improvements ongoing

---

## 🚀 Roadmap

- [x] Architecture design
- [x] Profile system design
- [x] Installer workflow design
- [ ] ISO build automation
- [ ] GitHub Actions CI/CD
- [ ] First boot system
- [ ] Stable v1.0 release

---

## 🤝 Contributing

Contributions are welcome:

- Improve package profiles
- Enhance installer modules
- Fix bugs
- Suggest features

---

## 📜 License

This project is licensed under **GPLv3**

---

## 🧠 Author

**Methos Linux Project**

Built with ❤️ on top of Arch Linux
