# 📡 AEP Core  
### Advanced Engagement Planner – Wireless Recon Framework  
**Made by Ray**

---

## 🚀 Overview

**AEP Core** adalah **framework wireless reconnaissance & attack planning** untuk kebutuhan **red team, pentesting lab, dan security research**.  
Tool ini berfokus pada **pengumpulan intel WiFi secara pasif**, analisis target, dan penyusunan **rencana serangan berbasis data** — **tanpa melakukan serangan otomatis**.

> Recon first. Decide smart. Act manually.

---

## ✨ Key Features

### 📶 Wireless Recon (Passive)
- Monitor mode WiFi scanning (Linux)
- Deteksi AP terbuka, WPA, WPA2, WPA3
- RSSI / signal strength profiling
- Channel detection & hopping
- Client count per AP

### 👁️ Hidden SSID Intelligence
- Deteksi Hidden SSID
- Mapping client ↔ BSSID
- Identifikasi channel Hidden SSID
- Guidance manual untuk SSID reveal (iw / tcpdump / airodump-ng)

### 🧠 Recon Analysis & Planning
- Target prioritization
- Attack feasibility hints
- Client density awareness
- Signal dominance evaluation
- Manual engagement recommendation

### 📊 Output & Reporting
- Clean terminal output (table-based)
- JSON report export
- Structured recon data
- Human-readable summaries
- Designed for decision-making, not automation

### 🛡️ Ethical-by-Design
- ❌ No automatic deauth
- ❌ No automatic cracking
- ❌ No MITM execution
- ❌ No exploit delivery
- ✅ Full operator control
- ✅ Lab & legal engagement oriented

---

## 🖥️ Example Output

============================================================
📡 AEP – Wireless Recon & Planner
Advanced Engagement Planner
Made by Ray
[📶] Interface : wlan1mon
[⏱️] Duration : 100s
[👁️] Hidden SSIDs detected : 2

BSSID CH RSSI ENC CLIENTS SSID
64:2c:ac:bc:ad:40 10 -54 WPA2/WPA3 7 RIFATHIOKE
f0:a7:31:b4:da:76 3 -85 WPA2/WPA3 12 MARVINDO
da:42:a1:9f:38:42 5 -84 WPA2/WPA3 0 <hidden>

[💾] Report saved: aep_report.json
[✅] Recon completed. Manual execution required.

yaml
Copy code

---

## 🧩 Workflow

Monitor Mode
↓
Passive Recon
↓
Hidden SSID Detection
↓
Client Mapping
↓
Target Analysis
↓
Manual Attack Planning

yaml
Copy code

AEP Core **tidak menggantikan** tools seperti `aircrack-ng`,  
tetapi **membuat penggunaannya lebih terarah dan profesional**.

---

## 🧪 Intended Use

✔️ Red Team internal  
✔️ Pentesting lab pribadi  
✔️ Wireless security research  
✔️ Education & learning  
✔️ Portfolio security project  

❌ Unauthorized access  
❌ Public WiFi abuse  
❌ Automated attacks  

---

## ⚙️ Requirements

- Linux
- Python 3.10+
- Monitor-mode capable WiFi adapter
- Root privileges (for sniffing)

---

## 🛣️ Roadmap

- Multi-band support (5GHz / 6GHz)
- Vendor / OUI fingerprinting
- Rogue AP detection heuristics
- Visualization (graph-based recon)
- Modular plugin architecture
- External recon tool integration

---

## 👨‍💻 Author

**Ray**  
Red Team • Wireless Security • Linux

> *Recon is intelligence. Attacks are decisions.*

---

## ⚠️ Disclaimer

This project is intended **strictly for educational and authorized security testing purposes**.  
Any misuse or unauthorized activity is the sole responsibility of the user.
