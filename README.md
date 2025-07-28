# 🧪 Forensic Workstation & Memory Analysis

This project documents the full setup and usage of a Windows-based forensic workstation, with memory acquisition and analysis performed using tools like **FTK Imager**, **Volatility**, **Redline**, and **Cyber Triage**.

📄 **Full Report (with screenshots & detailed steps)**:  
[Forensic_Report_PavithranCJ.pdf](https://github.com/pavithrancj/Cyber-Forensic-Tools/blob/main/Cyber%20Forensic%20Workstation.pdf)

---

## 🛠️ Tools Used

### Windows-based:
- FTK Imager
- Dumpit
- Cyber Triage
- Redline
- Wireshark
- VS Code
- 7-Zip

### Linux-based (via WSL):
- Volatility3
- Log2Timeline (plaso)
- Oletools
- pip3

---

## 🧰 Part 1: Setting Up the Forensic Workstation

- Installed **Windows 10** via VMware Workstation.
- Enabled **Windows Subsystem for Linux (WSL1)** and installed **Ubuntu 20.04**.
- Set the system **time zone to UTC** and enabled visibility for hidden files and file extensions.
- Created dedicated directories (`C:\Cases` and `C:\Tools`) for evidence and tools.
- **Disabled Microsoft Defender protections** and excluded forensic working folders from scans.
- Installed all necessary forensic tools in both Windows and WSL environments.

---

## 🧪 Part 2: Memory Acquisition & Analysis

### Volatility 3
- Captured memory using **FTK Imager**.
- Used commands like `pslist`, `dlllist`, and `netscan` to analyze active processes, loaded DLLs, and network activity.

### Redline
- Acquired memory and ran timeline analysis based on host-based indicators.
- Explored **system info**, file modifications, and suspicious behaviors.

### Cyber Triage
- Loaded memory image and reviewed flagged **bad/suspicious items**.
- Investigated items through file paths and system activity logs.

---

## 📌 Key Takeaways

- Set up an effective and safe forensic environment from scratch.
- Captured and analyzed live memory using multiple industry tools.
- Experienced hands-on incident investigation workflows.
- Developed structured documentation for forensic reporting.

---

## 📎 Reference Report

For detailed steps, screenshots, tool outputs, and command usage:  
📘 [`Reports/Forensic_Report_PavithranCJ.pdf`](https://github.com/pavithrancj/Cyber-Forensic-Tools/blob/main/Cyber%20Forensic%20Workstation.pdf)

---
