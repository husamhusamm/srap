<div align="center">


<p align="center">
  <img src="YOUR_IMAGE_URL_HERE" alt="S7 Swarm Core" width="220px" style="border-radius: 20px; border: 2px solid #ff0000; box-shadow: 0 0 40px #ff0000;">
</p>

<svg width="100%" height="40">
  <defs>
    <linearGradient id="neonGlow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#000000" />
      <stop offset="50%" stop-color="#ff0000" />
      <stop offset="100%" stop-color="#000000" />
    </linearGradient>
  </defs>
  <rect x="0" y="15" width="35%" height="4" fill="url(#neonGlow)">
    <animate attributeName="x" values="-35%; 100%; -35%" dur="2.8s" repeatCount="indefinite" />
  </rect>
  <rect x="0" y="22" width="20%" height="2" fill="url(#neonGlow)">
    <animate attributeName="x" values="100%; -20%; 100%" dur="3.8s" repeatCount="indefinite" />
  </rect>
</svg>

### 🔴 [ STATUS: ENGAGED ] 🔴  
**Advanced Framework for Multi-IP Session Automation**

<p align="center">
  <img src="YOUR_IMAGE_URL_HERE" alt="S7 Swarm Core" width="220px" style="border-radius: 20px; border: 2px solid #ff0000; box-shadow: 0 0 40px #ff0000;">
</p>

---

</div>

## 🌌 Overview
**S7 Swarm** is a powerful automation suite designed to launch up to **12 simultaneous Chromium instances**. Each session is completely isolated with its own browser profile and routed through a unique **Tor SOCKS circuit**.

---

## ⚡ Technical Arsenal:
* 🛡️ Session Sandbox: Isolated data directories for every window.
* 🧅 Identity Rotation: Automatic binding to individual Tor ports (9050-9061).
* 🖥️ Grid Matrix: Real-time window positioning based on screen resolution.
* 🚨 Emergency Stop: Integrated SIGINT trap to kill all processes with Ctrl+C.

---

## 🧠 System Logic
The core engine modifies the `torrc` configuration to allow multiple parallel connections. It utilizes tools like `xdotool` and `wmctrl` to orchestrate window geometry into a perfect tactical grid.

---

## 🛠️ Tactical Deployment (Command Center)

<div style="border:1px solid #ff0000; padding:10px; margin:10px; border-radius:10px; background:#0a0a0a;">
<pre>
# 1. Clone the Arsenal
git clone https://github.com/YourUsername/S7-Swarm.git
</pre>
</div>

<div style="border:1px solid #ff0000; padding:10px; margin:10px; border-radius:10px; background:#0a0a0a;">
<pre>
# 2. Enter Directory
cd S7-Swarm
</pre>
</div>

<div style="border:1px solid #ff0000; padding:10px; margin:10px; border-radius:10px; background:#0a0a0a;">
<pre>
# 3. Grant Execution Rights
chmod +x setup_s7.sh insta_tor3.sh
</pre>
</div>

<div style="border:1px solid #ff0000; padding:10px; margin:10px; border-radius:10px; background:#0a0a0a;">
<pre>
# 4. Run Environmental Setup
sudo ./setup_s7.sh
</pre>
</div>

<div style="border:1px solid #ff0000; padding:10px; margin:10px; border-radius:10px; background:#0a0a0a;">
<pre>
# 5. Launch the Swarm
./insta_tor3.sh
</pre>
</div>
