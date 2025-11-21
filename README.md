# 🕵️‍♂️ Wireshark Network Traffic Analysis  

## 📌 Project Overview
This project focuses on capturing, filtering, and analyzing real-time network traffic using Wireshark.  
The goal is to understand different network protocols, identify normal traffic patterns, and detect suspicious packets such as TCP resets or unknown DNS queries.

---

## 🎯 Objective
- Capture live network traffic  
- Apply protocol filters (HTTP, DNS, TCP Reset, TLS)  
- Analyze and interpret packet details  
- Save screenshots as evidence  
- Prepare findings for cybersecurity evaluation  

---

## 🛠 Tools Used
- **Wireshark (Windows 10/11)**
- Wi-Fi Network Adapter  
- Chrome / Any web browser  

---

## 📂 Project Contents
This repository contains:

- 📁 **Screenshots Folder** (8 screenshots):
  - HTTP Traffic  
  - DNS Traffic  
  - TLS Traffic  
  - TCP Reset Packets  
  - Normal and suspicious packets  

- 📄 **Report.pdf**  
  (Complete project documentation, methodology & findings)


  Saved manually via screenshots and documented findings.

---

## 🔍 Methodology (Step-by-Step)
1. Launched Wireshark on Windows  
2. Selected **Wi-Fi Adapter** for packet capture  
3. Visited websites (Google, YouTube, etc.) to generate traffic  
4. Applied filters:
   - `http`
   - `dns`
   - `tls`
   - `tcp.flags.reset == 1`
5. Analyzed each filtered packet  
6. Captured screenshots  
7. Organized files and uploaded to GitHub  

---

## 📑 Key Findings
### ✔ HTTP  
Normal unencrypted web traffic observed.

### ✔ DNS  
Multiple DNS queries detected including google.com, gstatic.com, windowsupdate.com.

### ✔ TLS  
Encrypted HTTPS communication was visible, showing secure connections.

### ✔ TCP Reset (RST)  
A few TCP reset packets observed — often indicates blocked or failed connections.

---

## ✅ Conclusion
Wireshark is a powerful tool for analyzing network traffic and detecting unusual behavior.  
This project helped in understanding:
- Protocol behavior  
- Secure vs insecure communication  
- Packet-level network monitoring  

This completes the Wireshark-based Traffic Analysis internship project.
