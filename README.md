🛡️ DDoS Stress Testing Tool

---

⚠️ DISCLAIMER

READ CAREFULLY

This tool was developed by Developer </> Извращенес for educational purposes and stress testing your own websites/servers only.

🔴 The developer is NOT responsible for:

· Any illegal use of this tool
· Targeting websites or servers without explicit permission
· Any damages resulting from misuse
· Violations of your country's laws

🟢 YOU are solely responsible for:

· Obtaining written permission before testing
· Complying with your local laws
· Any consequences of using this tool

---

📌 Purpose

This tool is designed for:

· ✅ Testing your own websites/servers for stress resistance
· ✅ Analyzing server performance under heavy load
· ✅ Identifying weaknesses in your infrastructure
· ✅ Hands-on training in DDoS defense

---

🎯 Features

Feature Description
🚀 Multiple Attacks SYN, UDP, HTTP, ICMP, Slowloris
⚡ High Performance Multithreading support
📱 Cross-platform Linux, Windows, Termux
🎨 Colored UI Real-time statistics display
🔒 Secure Packet encryption (optional)

---

📦 Installation

Termux:

```bash
pkg update && pkg upgrade
pkg install python git
git clone https://github.com/izvrashchenets/ddos-tool.git
cd ddos-tool
pip install -r requirements.txt
python ddos.py
```

Kali Linux / Linux (with sudo):

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install git python3 python3-pip -y
git clone https://github.com/izvrashchenets/ddos-tool.git
cd ddos-tool
sudo pip3 install -r requirements.txt
sudo python3 ddos.py
```

---

🚀 Quick Commands (Copy each separately)

📱 Termux Commands:

```bash
apt update && apt upgrade
```

```bash
pkg install git
```

```bash
apt update
```

```bash
pkg install python3
```

```bash
pkg install python -y
```

```bash
git clone https://github.com/AlmunharifHamoudi/DDos1.git
```

```bash
pip install -r requirements.txt
```

```bash
cd DDos1
```

```bash
python DDos.py
```

💻 Kali Linux / Linux Commands (with sudo):

```bash
sudo apt update && sudo apt upgrade -y
```

```bash
sudo apt install git -y
```

```bash
sudo apt update
```

```bash
sudo apt install python3 -y
```

```bash
sudo apt install python3-pip -y
```

```bash
git clone https://github.com/AlmunharifHamoudi/DDos1.git
```

```bash
cd DDos1
```

```bash
sudo pip3 install -r requirements.txt
```

```bash
sudo python3 DDos.py
```

---

💡 Usage Examples

```bash
# Basic attack
python ddos.py -t 192.168.1.1 -p 80 -m http

# Advanced attack with threads
python ddos.py -t example.com -p 443 -m syn -T 500 -d 60

# Show help
python ddos.py -h
```

---

🔧 Requirements

· Python 3.6+
· Required packages (auto-installed via requirements.txt):
  · scapy
  · colorama
  · requests
  · threading

---

📝 Notes

· Run with root/administrator privileges for full functionality
· Some attacks require raw socket permissions
· Use responsibly and only on authorized targets

---

📜 License

This project is for educational purposes only. Use at your own risk.

---

⚠️ REMEMBER: Always get written permission before testing any system you don't own!
