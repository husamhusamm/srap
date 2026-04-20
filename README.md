<div align="center">

<img src="https://capsule-render.vercel.app/render?type=thicker&color=000000&customColorList=10&height=300&section=header&text=S7%20SWARM&fontSize=90&animation=fadeIn&fontAlignY=38&desc=NEXT-GEN%20MULTI-SESSION%20TOR%20AUTOMATION&descAlignY=62&descSize=20&fontColor=ff0000" width="100%" />

[![License](https://img.shields.io/badge/LICENSE-MIT-red.svg?style=for-the-badge&logo=github)](https://github.com/)
[![Kernel](https://img.shields.io/badge/PLATFORM-LINUX-red.svg?style=for-the-badge&logo=linux)](https://www.linux.org/)
[![Network](https://img.shields.io/badge/NETWORK-TOR-red.svg?style=for-the-badge&logo=tor-project)](https://www.torproject.org/)

<p align="center">
  <img src="https://via.placeholder.com/200/000000/ff0000?text=S7+SWARM" alt="S7 Swarm Logo" width="200px" style="border-radius: 50%; border: 3px solid #ff0000; box-shadow: 0 0 30px #ff0000;">
</p>

### 🔴 [ PROTOCOL: THE SWARM IS ACTIVE ] 🔴
**High-Performance Multi-Session Browser Automation via Anonymous Tor Circuits**

---

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="3px">

</div>

## 🌌 Project Overview
**S7 Swarm** is a sophisticated Linux-based automation framework designed to orchestrate up to **12 simultaneous Chromium sessions**. Each session is cryptographically isolated and routed through its own unique **Tor SOCKS circuit**, ensuring complete IP diversity and identity protection across the swarm.

### ⚡ Core Cyber-Capabilities:
* 🛡️ **Session Isolation:** Each instance utilizes a unique, temporary browser profile.
* 🧅 **Multi-IP Routing:** Automatic binding to distinct Tor SOCKS ports (9050-9061).
* 🖥️ **Dynamic Grid Layout:** Intelligent window positioning based on your real-time screen resolution.
* 🚨 **Fail-Safe Mechanism:** One-touch termination (Ctrl+C) that cleans up all processes and sessions instantly.

---

<div align="left">

## 🛠️ System Prerequisites
> [!IMPORTANT]
> This framework is optimized for Debian-based distributions (Kali Linux, Ubuntu, Parrot OS).

The following dependencies are managed automatically by the setup script:
- `Tor Service` (Background daemon)
- `Chromium-Browser` (Engine)
- `Xdotool` & `Wmctrl` (Window Control)
- `X11-Utils` (Screen Detection)

---

## 🚀 Deployment & Operations
Execute the following commands in your terminal to initialize the swarm:

### 1️⃣ System Preparation (One-time)
Authorize and run the setup script to configure services and ports:
```bash
chmod +x setup_s7.sh && ./setup_s7.sh
