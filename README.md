<div align="center">

# 🔗 USBlink  
### **A Modular Python Toolkit for USB Threat Detection, BadUSB Analysis & Device Security**

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey.svg)]()
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()

</div>

---

USBlink is a **lightweight, security-focused Python framework** designed to detect suspicious USB activity in real time.  
It provides a hands-on demonstration of **BadUSB detection, device monitoring, file anomaly analysis, and automated reporting**, making it a powerful project for **cybersecurity students, VAPT learners, and recruiters evaluating practical skills**.

This project showcases real-world concepts used in **digital forensics, endpoint security, and hardware threat analysis**, delivered in a clean, modular structure.

---

## 🚀 What USBlink Offers

- 🔍 **Real-Time USB Monitoring** — Detect device connections instantly  
- 🛡️ **BadUSB Heuristics Engine** — Flags spoofed or suspicious devices  
- 📂 **File Activity Observation** — Watch USB file transfers for anomalies  
- 📊 **Automated Reports** — Timestamped logs saved to `/reports`  
- ⚙️ **Modular Architecture** — Add scanners easily inside `modules/`  
- 🖥️ **CLI-Based Execution** — Simple command for interviews & labs  

USBlink is built to be **clean, readable, and recruiter-ready**.

---

## 🛠️ Installation & Setup

```bash
git clone https://github.com/Hell-Mava/USBlink.git
cd USBlink

python -m venv venv

# Linux / macOS
source venv/bin/activate

# Windows
venv\Scripts\activate

pip install -r requirements.txt
▶️ Running USBlink
bash
Copy code
python usblink.py run
Example output:

yaml
Copy code
[+] Monitoring USB devices...
[+] Device detected: Kingston USB 3.0
[!] Suspicious device flagged: Unknown Vendor ID
Report saved: report_2025-11-15.txt
📂 Repository Structure
bash
Copy code
USBLINK/
│── usblink.py          # Main execution script
│── modules/            # Detection and scanning modules
│── utils/              # Helper functions
│── reports/            # Auto-generated scan reports
│── requirements.txt    # Dependencies
│── README.md           # Documentation
│── .gitignore          # Ignored files
📌 Why This Project Is Useful
🎓 Students: Hands-on cybersecurity experience

👔 Recruiters: Demonstrates real detection logic

🧪 Labs: Useful for monitoring & USB security testing

🛡️ VAPT Learners: Understand USB-based attack vectors

USBlink focuses on real-world defensive concepts, making it a strong portfolio project.

📜 License
This project is licensed under the MIT License.

👨‍💻 Author
Sohel Shaik
GitHub: Hell-Mava
Email: 1914sohel@gmail.com

<div align="center">
✨ USBlink — A small tool with strong defensive potential. ✨

</div> ```
