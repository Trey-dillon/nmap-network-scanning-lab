# 🔎 Nmap Network Scanning & Enumeration Lab

![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanning-red?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Focus-Security%20Assessment-blue?style=for-the-badge)

---

# 📌 Overview

This project documents my hands-on practice using Nmap for network discovery, port scanning, service enumeration, and security assessment.

The goal of this lab is to develop skills commonly used in cybersecurity roles, including vulnerability assessment and network reconnaissance.

---

# Lab Environment

## Tools Used

- Nmap
- Linux Terminal
- VirtualBox
- Windows/Linux Virtual Machines

---

# Scanning Techniques Practiced

## Host Discovery

Identified active systems on a network using:

- Ping scans
- Host discovery techniques
- Network mapping

---

## Port Scanning

Performed scans to identify:

- Open ports
- Available services
- Network exposure

Examples:

- TCP scanning
- UDP scanning
- Service detection

---

## Service Enumeration

Collected information about:

- Running services
- Service versions
- Operating system details

---

# Lab Exercises

## Network Discovery

Objective:

Identify available hosts within a test environment.

Skills practiced:

- Network mapping
- Host identification
- Address discovery


---

## Port Analysis

Objective:

Identify exposed services.

Analyzed:

- Open ports
- Common services
- Potential security risks


---

## Service Detection

Objective:

Gather additional information about discovered services.

Practiced:

- Version detection
- OS fingerprinting
- Basic enumeration

---

# Security Concepts

Skills demonstrated:

- Network reconnaissance
- Attack surface awareness
- Vulnerability identification
- Security assessment methodology

---

# Screenshots

## 1. Host Discovery

![Host Discovery](screenshots/Nmap%201%20host%20directory.png)

Used Nmap's host discovery capabilities to identify active devices within the lab network. This scan provides a quick inventory of reachable systems before performing more detailed enumeration.

---

## 2. Basic TCP Port Scan

![Basic TCP Port Scan](screenshots/Nmap%202%20Basic%20TCP%20Port%20Scan.png)

Performed a default TCP port scan to identify open ports and the services exposed by the target system. This establishes a baseline understanding of the target's network footprint.

---

## 3. Service Version Detection

![Service Version Detection](screenshots/Nmap%203%20Service%20Version%20Detection.png)

Used the `-sV` option to detect service versions running on open ports. Identifying software versions helps determine potential vulnerabilities and supports system inventory.

---

## 4. Operating System Detection

![Operating System Detection](screenshots/Nmap%204%20Operating%20System%20Detection.png)

Performed operating system fingerprinting using Nmap's OS detection capabilities to estimate the target machine's operating system based on network characteristics.

---

## 5. Aggressive Scan

![Aggressive Scan](screenshots/Nmap%205%20Aggressive%20Scan.png)

Executed an aggressive scan (`-A`) combining service detection, operating system fingerprinting, default NSE scripts, and traceroute to gather comprehensive information about the target system.

---

# Future Improvements

- Add vulnerability scanning results
- Compare scan results before/after hardening
- Document defensive mitigation steps
- Add automated scanning scripts
