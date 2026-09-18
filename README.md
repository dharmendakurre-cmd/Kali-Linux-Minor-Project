# Kali-Linux-Minor-Project
Cyber Security Minor Project: Kali Linux OS, MAC Spoofing &amp; User Management

  Project Overview
This repository contains the complete documentation, execution logs, and practical proof of the Cyber Security Minor Project focused on Kali Linux OS administration, network security, and user privilege control. The project demonstrates essential offensive and defensive security fundamentals within a secure, virtualized lab environment using VMware Workstation.   

 [Key Topics & Practical Tasks Implemented]

1. OS Installation & System Verification: Deployed Kali Linux (Rolling Release) on VMware Workstation in an isolated virtual environment. Successfully verified active user session and Linux kernel release architecture using core Linux utilities (whoami and cat /etc/os-release).  

2. Package Management & Security Patching:  Maintained operational security and resolved software vulnerabilities by refreshing repository package indices and upgrading essential penetration testing toolchains via sudo apt update and sudo apt upgrade.  

3. Layer-2 Anonymity via MAC Address Spoofing:  Demonstrated network identity manipulation using the macchanger utility. Temporarily isolated the virtual network interface (eth0), assigned a randomized spoofed MAC address, and validated permanent versus current hardware addressing to bypass MAC filtering and avoid device tracking.   

4. User Management & Privilege Delegation (PoLP):  Enforced the Principle of Least Privilege by provisioning a dedicated standard user (secuser). Granted administrative root-level access via the sudo group and verified administrative task execution through session switching (su - secuser) and root elevation verification.   


Repository Contents: Dharmendra_Kurre_Minor_Project.pdf: Comprehensive project report containing theoretical explanations, command tables, and terminal verification screenshots for each phase.   
