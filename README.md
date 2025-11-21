# Wireshark Network Traffic Analysis

## 📌 Project Overview
This project analyzes live network traffic using Wireshark.  
The goal is to observe different types of network packets (HTTP, DNS, TCP Reset, TLS)  
and identify normal and suspicious traffic patterns.

---

## 📂 Contents in This Repository
This repository includes:

- 📸 **Screenshots Folder** (all 8 screenshots taken during analysis)
- 📝 **Report.pdf** (summary of findings and methods)
- 🧪 **Capture files** (if available)
- 📄 **README.md** (this file)

---

## 🛠 Tools Used
- Wireshark  
- Windows 10 / 11  
- Google Chrome / Browser  
- Wi-Fi Network Interface  

---

## 🚀 Steps Performed
1. Opened Wireshark  
2. Started live packet capture on Wi-Fi  
3. Opened websites (Google, YouTube) to generate traffic  
4. Stopped capture and applied filters:
   - `http`
   - `dns`
   - `tcp.flags.reset == 1`
   - `tls`
5. Took screenshots of each filtered result  
6. Identified suspicious packets (RST connections, unknown IPs)  
7. Saved everything into project folder  
8. Uploaded project to GitHub  

---

## 🔍 Findings Summary
- Normal HTTP & DNS traffic was observed  
- TLS encrypted packets from HTTPS sites  
- TCP Reset packets showing failed or blocked connections  
- Unknown IP addresses likely from CDNs or background services  

---

## 📢 Conclusion
Wireshark helped to analyze different types of traffic, detect unusual connections,  
and understand how data flows inside a network. This is essential for cybersecurity  
monitoring, threat detection, and network troubleshooting.

---

## 📬 Author
Internship Project by **Deepansh Reddy**

Submitted to **Codect Technologies**  
Project Name: *Network Traffic Analysis using Wireshark*
