# Networkwalks-MUHAMMED-B084L-WK1-PM1-CyberSecurity-Lab-Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Waqas%20Karim%20CCIE-C00000?style=flat-square" />
</p>

Mais Cyber Security Lab Setup
Week 1 – Project Module 1: Cybersecurity Lab Setup
# Project Objective
The objective of this project was to set up a virtual cybersecurity testing laboratory using Oracle VirtualBox and Kali Linux for practical cybersecurity learning.

# Tools Used
- Oracle VirtualBox
- Kali Linux
- Windows Host Operating System

# Implementation Steps
 1. VirtualBox Setup
I used Oracle VirtualBox to create and manage my Kali Linux virtual machine.
 2. NAT Network Configuration
I configured a NAT Network with the subnet `10.0.0.0/24` as required by the internship assignment.
 4. Kali Linux IP Configuration
I configured Kali Linux to use the IP address `10.0.0.2/24` and the default gateway `10.0.0.1`
```text
IP Address: 10.0.0.2
Subnet Mask: 255.255.255.0
Gateway: 10.0.0.1
DNS: 8.8.8.8
```
 6. Virtual Machine Settings
I configured shared clipboard, drag-and-drop and shared folder settings to support communication between my host computer and Kali Linux.
 7. Network Connectivity Testing
I used Linux networking commands such as `ip addr`, `ip route` and `ping` to verify the network configuration and test connectivity.
 8. Virtual Machine Snapshot
I created a snapshot of my Kali Linux virtual machine to preserve the working configuration.

# Challenges Encountered
During the configuration, I encountered an IP addressing issue where Kali Linux initially received `10.0.0.3/24` instead of the required `10.0.0.2/24`.
I investigated the network configuration using Linux commands and adjusted the settings until the required IP address was assigned successfully.
This helped me understand IP addressing, DHCP, NAT networking and network troubleshooting.

```bash
sudo nmcli connection modify "Wired connection 1" ipv4.dad-timeout 0
```

# Screenshots
The screenshots included in this repository provide evidence of the virtual machine configuration, network settings and connectivity tests.

# Conclusion
This project helped me gain practical experience in setting up a virtual cybersecurity laboratory, configuring network adapters, assigning IP addresses and troubleshooting network connectivity issues.

The completed lab will serve as an environment for future cybersecurity practical exercises.
