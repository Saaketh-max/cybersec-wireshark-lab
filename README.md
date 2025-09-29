# cybersec-wireshark-report with .pcap export.
# 🛡️ Wireshark Protocol Analysis — Cybersecurity Wireshark Lab.

This repository documents a hands-on network traffic analysis using Wireshark. The goal is to capture live packets, identify multiple protocols, and summarize findings in a structured report. This exercise is part of a cybersecurity internship focused on practical network diagnostics and protocol inspection.

---

## 🔗 Wireshark Installation

Download and install Wireshark from the official site:  
👉 [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)

---

## ⚙️ Step-by-Step Instructions (Linux & Windows)

### 1️⃣ Identify Active Network Interface (Linux)
```bash
ip a


2️⃣ Launch Wireshark

    Linux:
    bash
sudo wireshark
Windows:

    Open Wireshark from Start Menu (Run as Administrator if needed)

3️⃣ Start Capture

    Select your active interface (e.g., eth0, enp0s3, Wi-Fi)

    Click the blue shark fin icon to begin capturing


4️⃣ Generate Traffic

    Open a terminal or browser and run:
ping -c 5 example.com        # Linux
curl http://example.com      # Linux

Or on Windows:
ping example.com
curl http://example.com

5️⃣ Stop Capture

    After ~1 minute, click the red square icon in Wireshark to stop

6️⃣ Filter by Protocol

Use the top filter bar in Wireshark:

    http

    dns

    tcp

    icmp

7️⃣ Export Capture

    Go to File → Save As → capture_report.pcap

    Save in your desired folder (e.g., wireshark_reports/)

8️⃣ Summarize Findings

Create a markdown report with:

    Protocols identified

    Sample packet details (source/destination IP, ports, info)

    Observations and insights

📁 Files Included

    capture_report.pcap — Raw packet capture

    summary.md — Protocol analysis report

    eth0.packets.txt — Exported packet log (optional)

🧠 Author

D.V.S. Saaketh Cybersecurity Intern | GD Goenka University Specialized in protocol analysis, system diagnostics, and ethical troubleshooting



---

Let me know when you're ready to push this to GitHub — I can guide you through `git init`, commits, and publishing the repo. Or if you want to add badges, screenshots, or a license, I’ll help you level it up.
