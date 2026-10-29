# Networkwalks-MUHAMMED-B084L-WK1-PM1-CyberSecurity-Lab-Setup
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
 3. Kali Linux IP Configuration
I configured Kali Linux to use the IP address `10.0.0.2/24` and the default gateway `10.0.0.1`
 4. Virtual Machine Settings
I configured shared clipboard, drag-and-drop and shared folder settings to support communication between my host computer and Kali Linux.
 5. Network Connectivity Testing
I used Linux networking commands such as `ip addr`, `ip route` and `ping` to verify the network configuration and test connectivity.
 6. Virtual Machine Snapshot
I created a snapshot of my Kali Linux virtual machine to preserve the working configuration.

# Challenges Encountered
During the configuration, I encountered an IP addressing issue where Kali Linux initially received `10.0.0.3/24` instead of the required `10.0.0.2/24`.
I investigated the network configuration using Linux commands and adjusted the settings until the required IP address was assigned successfully.
This helped me understand IP addressing, DHCP, NAT networking and network troubleshooting.

# Screenshots
The screenshots included in this repository provide evidence of the virtual machine configuration, network settings and connectivity tests.

# Conclusion
This project helped me gain practical experience in setting up a virtual cybersecurity laboratory, configuring network adapters, assigning IP addresses and troubleshooting network connectivity issues.

The completed lab will serve as an environment for future cybersecurity practical exercises.
