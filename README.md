عدل ع 
# 🛡️ DDoS Stress Testing Tool

---

## ⚠️ DISCLAIMER

**READ CAREFULLY**

> This tool was developed by **Developer </> Извращенес** for educational purposes and stress testing your own websites/servers only.
>
> **🔴 The developer is NOT responsible for:**
> - Any illegal use of this tool
> - Targeting websites or servers without explicit permission
> - Any damages resulting from misuse
> - Violations of your country's laws
>
> **🟢 YOU are solely responsible for:**
> - Obtaining written permission before testing
> - Complying with your local laws
> - Any consequences of using this tool

---

## 📌 Purpose

This tool is designed for:
- ✅ Testing your own websites/servers for stress resistance
- ✅ Analyzing server performance under heavy load
- ✅ Identifying weaknesses in your infrastructure
- ✅ Hands-on training in DDoS defense

---

## 🎯 Features

| Feature | Description |
|---------|-------------|
| 🚀 Multiple Attacks | SYN, UDP, HTTP, ICMP, Slowloris |
| ⚡ High Performance | Multithreading support |
| 📱 Cross-platform | Linux, Windows, Termux |
| 🎨 Colored UI | Real-time statistics display |
| 🔒 Secure | Packet encryption (optional) |

---

## 📦 Installation

### Termux:
```bash
pkg update && pkg upgrade
pkg install python git
git clone https://github.com/izvrashchenets/ddos-tool.git
cd ddos-tool
pip install -r requirements.txt
python ddos.py
