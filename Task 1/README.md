# 📡 Network Packet Sniffer using Python (Scapy)

## 📌 Project Overview
This project is a **Network Packet Sniffer** developed in Python using the Scapy library. It captures and analyzes network packets in real-time.

The tool extracts:
- Source IP address  
- Destination IP address  
- Protocol type (TCP/UDP)  
- Packet payload  

---

## 🎯 Objectives
- Capture live network traffic  
- Analyze packet structure  
- Identify protocols (TCP/UDP)  
- Understand data flow in networks  

---

## 🛠️ Technologies Used
- Python  
- Scapy  
- VS Code  
- Windows/Linux  

---

## ⚙️ Installation & Setup

### 1. Install Python
```bash
python --version
```

### 2. Install Scapy
```bash
pip install scapy
```

### 3. Run the Program
```bash
python task1.py
```

💡 Run as Administrator (Windows) or:
```bash
sudo python task1.py
```

---

## 📜 Code Explanation

### Import Libraries
```python
from scapy.all import sniff, IP, TCP, UDP
```

### Packet Processing
- Extracts source & destination IP  
- Detects protocol  
- Displays payload  

### Sniffing Function
```python
sniff(prn=process_packet, store=False)
```

---

## 🧪 Sample Output
```
--- Packet Captured ---
Source IP: 104.18.39.21
Destination IP: 192.168.10.9
Protocol: TCP
Payload: b'...'
```

---

## 🚀 Features
- Real-time packet capture  
- Protocol detection  
- Lightweight  
- Easy to understand  

---

## ⚠️ Limitations
- Cannot decrypt HTTPS traffic  
- No filtering applied  
- Requires admin privileges  

---

## 🔮 Future Improvements
- Add packet filtering  
- Save packets to file  
- GUI interface  
- Traffic statistics  

---

## 🔐 Ethical Use
This project is for **educational purposes only**.  
Do not use without permission.

---

## 👨‍💻 Author
Muhammad Awais Asif  
