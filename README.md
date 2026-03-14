<div align="center">

# 🌐 CyberSH Port Scanner

[![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)](#)
[![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)](#)
[![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Termux-lightgrey.svg)](#)
[![License](https://img.shields.io/badge/License-MIT-red.svg)](#)

**CyberSH Port Scanner** is a fast, lightweight, and efficient network scanning tool designed to quickly discover and identify active devices across specific IP ranges. It excels at detecting network equipment such as MikroTik routers, DVR/NVR systems, H3C, ZTE, and Ubiquiti devices.

</div>

---

## 📑 Table of Contents
- [Features](#-features)
- [Screenshot](#-screenshot)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
  - [Linux (Ubuntu/Debian)](#-linux-ubuntudebiankali)
  - [Termux (Android)](#-termux-android)
- [Usage](#-usage)
- [Disclaimer](#-disclaimer)
- [Contact & Support](#-contact--support)

---

## ✨ Features

* **High-Speed Scanning:** Optimized for rapid discovery across large IP blocks and subnets.
* **Intelligent Device Fingerprinting:** Automatically identifies and categorizes common network hardware (e.g., MikroTik, Cambium, DVRs).
* **Cross-Platform Compatibility:** Runs flawlessly on standard Linux distributions, lightweight server environments, and Android devices via Termux.
* **Minimalist Interface:** Clean, easily parsable terminal output designed for quick reading.

---

## 📸 Screenshot

<a href="https://ibb.co.com/N6PHt2gW"><img src="https://i.ibb.co.com/HDskBTLG/Gemini-Generated-Image-uxs731uxs731uxs7.png" alt="Gemini-Generated-Image-uxs731uxs731uxs7" border="0"></a>
---

## ⚙️ Prerequisites

Ensure your system meets the following requirements before installation:
* **Python 3.x** installed.
* **Git** installed for cloning the repository.
* An active internet or local network connection.

---

## 🚀 Installation

### 🐧 Linux (Ubuntu/Debian/Kali)

Open your terminal and execute the following commands to set up the scanner:

```bash
# 1. Update your system packages
sudo apt update && sudo apt upgrade -y

# 2. Install required dependencies
sudo apt install git python3 python3-pip -y

# 3. Clone the repository
git clone https://github.com/ShTasrif/PortScanner.git

# 4. Navigate into the directory
cd PortScanner

# 5. Install Python requirements
pip3 install -r requirements.txt

# 6. Run the tool
python3 main.py
```
### Termux 
```bash

# 1. Update your system packages
pkg update && pkg upgrade -y

# 2. Install required dependencies
pkg install git python3 python3-pip -y

# 3. Clone the repository
git clone https://github.com/ShTasrif/PortScanner.git

# 4. Navigate into the directory
cd PortScanner

# 5. Install Python requirements
pip3 install -r requirements.txt

# 6. Run the tool
python3 main.py
