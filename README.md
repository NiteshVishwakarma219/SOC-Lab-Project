# SOC Cyber Security Home Lab

## Project Description
This project demonstrates the creation of a Cyber Security Home Lab designed to simulate real-world Security Operations Center (SOC) environments.  
The goal of this lab is to practice cyber attack simulation, network monitoring, and security investigation.

This lab helps develop practical skills required for:
- SOC Analyst
- Cyber Security Analyst
- Blue Team Roles

---

## Lab Architecture

Attacker Machine: Kali Linux  
Target Machine: Windows 10  
Virtualization Platform: VirtualBox  

Network Setup:
Kali Linux (Attacker) → Internal Network → Windows Target Machine

---

## Objectives of This Project
- Build a working cyber security lab
- Simulate real-world attacks
- Understand attacker techniques
- Practice network monitoring
- Prepare for SOC analyst role

---

## Tools and Technologies Used
- Kali Linux
- Windows 10
- VirtualBox
- Nmap
- Metasploit Framework
- Wireshark
- Basic Networking

---

## Lab Setup Process

### Step 1: Virtualization Setup
Installed VirtualBox and created two virtual machines:
- Kali Linux
- Windows 10

### Step 2: Network Configuration
Configured both machines on the same internal network to allow communication.

### Step 3: System Preparation
Updated Kali Linux and verified installed security tools.

### Step 4: Connectivity Testing
Verified network connectivity between machines using ping and IP configuration.

---

## Security Testing Performed

### Network Scanning
Used Nmap to discover open ports and services running on the target machine.

Example: nmap -sV <target-ip>


### Enumeration
Identified available services and possible vulnerabilities.

### Traffic Monitoring
Observed network packets using Wireshark.

---

## Screenshots
Project screenshots are available in the **screenshots folder**:

- Lab environment setup
- Virtual machines running
- Network configuration
- Attack simulation
- Scan results

---

## Skills Demonstrated
- Cyber Security Lab Setup
- Network Scanning
- Threat Identification
- Security Monitoring
- Incident Investigation Basics

---

## What I Learned
Through this project, I learned:

- How attackers scan and analyze networks
- How to build a SOC practice lab
- How security analysts detect suspicious activity
- Basics of real-world cyber security operations

---

## Future Enhancements
Next upgrades planned for this lab:

- SIEM integration (Splunk / Wazuh)
- Attack detection alerts
- Log monitoring system
- SOC dashboard
- Threat intelligence integration

---

## Project Status
Active – Continuous Improvement

---

## Author
Nitesh Vishwakarma  
Aspiring SOC Analyst | Cyber Security Learner

---

## Connect With Me
LinkedIn: (Add your LinkedIn profile link here)
GitHub: (Add your GitHub profile link here)