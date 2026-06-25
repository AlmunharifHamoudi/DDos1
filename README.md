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

Termux Installation Commands:

Copy and run each command one by one:

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
cd DDos1
```

```bash
pip install -r requirements.txt
```

```bash
python DDos.py
```

---

🚀 Usage

Interactive Mode:

```bash
python DDos.py
```

Command Line:

```bash
python DDos.py --target <IP/DOMAIN> --port <PORT> --method <METHOD> --time <SECONDS>
```

Parameters:

```
-t, --target   : Target IP or Domain
-p, --port     : Port number (default: 80)
-m, --method   : Attack method (syn, udp, http, icmp, slow)
-t, --time     : Duration in seconds
-th, --threads : Number of threads (default: 100)
```

Examples:

```bash
python DDos.py -t example.com -p 443 -m syn -t 60
```

```bash
python DDos.py -t 192.168.1.1 -p 53 -m udp -th 500 -t 30
```

```bash
python DDos.py -t mysite.com -p 80 -m http -t 120
```

---

📊 Interface Preview

```
╔═══════════════════════════════════════╗
║   💀 DDoS Stress Tester v2.1         ║
║   🛡️ By: Извращенес                 ║
╠═══════════════════════════════════════╣
║   Target: example.com                 ║
║   Port: 80                            ║
║   Method: SYN Flood                   ║
║   Threads: 150                        ║
║   Time: 60s                           ║
╠═══════════════════════════════════════╣
║   📊 Packets Sent: 1,245,789         ║
║   ⚡ Speed: 24.5K/s                  ║
║   📈 Success: 99.8%                  ║
║   ⏱️ Time Left: 45s                  ║
╚═══════════════════════════════════════╝
```

---

🔧 Requirements

```
Python 3.7+
scapy
socket
threading
requests
colorama
```

Install requirements manually if needed:

```bash
pip install scapy requests colorama termcolor
```

---

🛑 Final Warning

```
⚠️ THIS TOOL IS A DOUBLE-EDGED SWORD ⚠️

Use it wisely and only within legal frameworks.
Developer Извращенес states its purpose is:
"EDUCATION AND TESTING YOUR OWN SITES, NOT DESTRUCTION"

🔐 Use responsibly!
```

---

📝 License

This tool is for educational purposes only. Unauthorized use is prohibited.

---

📞 Contact

· GitHub: github.com/AlmunharifHamoudi

---

Remember: With great power comes great responsibility! 🕸️
