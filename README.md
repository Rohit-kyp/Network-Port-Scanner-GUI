# Network-Port-Scanner-GUI
A Python-based GUI application that performs multi-threaded TCP port scanning to identify open ports on a target system. Built using Tkinter and socket programming, it provides real-time results, service detection, and a user-friendly interface without requiring command-line knowledge.
# 🔍 Network Port Scanner GUI

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.7+-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/GUI-Tkinter-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

---

## 📌 Overview

**Network Port Scanner GUI** is a high-performance, multi-threaded TCP port scanner with an intuitive graphical interface.

It is designed for:
- 🛡️ Cybersecurity learners  
- 🌐 Network administrators  
- 👨‍💻 Beginners exploring networking  

👉 No command-line knowledge required.

---

## ✨ Key Features

- ⚡ Multi-threaded scanning (up to 500 threads)
- 🖥️ Simple and clean GUI
- 📡 Real-time port detection
- 🔎 Service identification (HTTP, SSH, FTP, etc.)
- ⏹️ Stop scan anytime
- 💾 Save results to file
- 🌍 Cross-platform support
- 📦 Zero external dependencies

---

## 🧠 Architecture

### Core Components:
- **PortScanner** → Backend logic  
- **ScannerGUI** → Frontend interface  
- **Queue** → Thread communication  
- **Semaphore** → Thread control  

---

## ⚙️ Tech Stack

| Technology | Purpose |
|----------|--------|
| Python | Core language |
| Tkinter | GUI |
| Socket | Network scanning |
| Threading | Concurrency |
| Queue | Data transfer |

---

## 📸 Screenshots

### 🖥️ GUI Interface
![GUI](screenshots/ui.png)

### ⚡ Scanning in Progress
![Scanning](screenshots/scanning.png)

### 📊 Results Output
![Results](screenshots/results.png)

---

## 🚀 Getting Started

