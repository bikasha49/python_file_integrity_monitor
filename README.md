# 🛡️ Python File Integrity Monitor (FIM)

> **Role:** Cybersecurity Analyst Portfolio Project
> **Concept:** Integrity Monitoring & Intrusion Detection

## 📌 Project Overview
A custom-built **File Integrity Monitor (FIM)** developed in Python. This tool monitors a target directory for unauthorized changes, creating a baseline of file hashes (SHA-512) and continuously checking for modifications, creations, or deletions.

This project demonstrates the core concept of **Integrity** within the CIA Triad, a fundamental principle of Security Operations Center (SOC) activities.

## 🚀 Features
* **SHA-512 Hashing:** Uses robust cryptographic hashing to fingerprint files (significantly more secure than MD5).
* **Baseline Creation:** Generates a "known-good" state of the target directory to identify deviations.
* **Real-Time Monitoring:** Continuously scans for unauthorized changes in an infinite loop.
* **Granular Alerting:** Distinguishes between three types of incidents:
    * `[NEW]` File Created
    * `[CHANGED]` File Modified (Integrity Compromised)
    * `[DELETED]` File Removed

## 🛠️ Technology Stack
* **Language:** Python 3
* **Environment:** Kali Linux (Compatible with Windows/macOS)
* **Libraries:** `os`, `hashlib`, `time`

## 📸 Screenshots

### 1. Real-Time Detection ("The Money Shot")
*The FIM detects a file modification instantly as it happens. The split-screen view shows the attack commands (left) and the automated detection (right).*
# 🛡️ Python File Integrity Monitor (FIM)

> **Role:** Cybersecurity Analyst Portfolio Project
> **Concept:** Integrity Monitoring & Intrusion Detection

## 📌 Project Overview
A custom-built **File Integrity Monitor (FIM)** developed in Python. This tool monitors a target directory for unauthorized changes, creating a baseline of file hashes (SHA-512) and continuously checking for modifications, creations, or deletions.

This project demonstrates the core concept of **Integrity** within the CIA Triad, a fundamental principle of Security Operations Center (SOC) activities.

## 🚀 Features
* **SHA-512 Hashing:** Uses robust cryptographic hashing to fingerprint files (significantly more secure than MD5).
* **Baseline Creation:** Generates a "known-good" state of the target directory to identify deviations.
* **Real-Time Monitoring:** Continuously scans for unauthorized changes in an infinite loop.
* **Granular Alerting:** Distinguishes between three types of incidents:
    * `[NEW]` File Created
    * `[CHANGED]` File Modified (Integrity Compromised)
    * `[DELETED]` File Removed

## 🛠️ Technology Stack
* **Language:** Python 3
* **Environment:** Kali Linux (Compatible with Windows/macOS)
* **Libraries:** `os`, `hashlib`, `time`

## 📸 Screenshots

### 1. Real-Time Detection ("The Money Shot")
*The FIM detects a file modification instantly as it happens. The split-screen view shows the attack commands (left) and the automated detection (right).*
![Real Time Detection](https://github.com/YOUR_USERNAME/Python-File-Integrity-Monitor/blob/main/demo.png?raw=true)

### 2. Baseline Creation
*Establishing the initial "Known Good" state. The script calculates SHA-512 hashes for all target files to create a fingerprint.*
![Baseline Creation](https://github.com/YOUR_USERNAME/Python-File-Integrity-Monitor/blob/main/Baseline.png?raw=true)

## 💻 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Python-File-Integrity-Monitor.git](https://github.com/YOUR_USERNAME/Python-File-Integrity-Monitor.git)

### 2. Baseline Creation
*Establishing the initial "Known Good" state. The script calculates SHA-512 hashes for all target files to create a fingerprint.*
![Baseline Creation](https://github.com/YOUR_USERNAME/Python-File-Integrity-Monitor/blob/main/Baseline.png?raw=true)

## 💻 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Python-File-Integrity-Monitor.git](https://github.com/YOUR_USERNAME/Python-File-Integrity-Monitor.git)
