# Nmap Basics

This repository contains my learning notes and basic practical commands related to Nmap and network scanning.

## Topics Covered

### 1. Nmap Installation & Version Check
Understanding how to install Nmap and verify the installed version.

```bash
nmap --version

2. IP Address Identification

Finding the system IP address using Windows command prompt.

ipconfig

3. Basic Port Scanning

Scanning a target to identify open ports.

nmap <IP_ADDRESS>

4. Service & Version Detection

Detecting running services and their versions.

nmap -sV <IP_ADDRESS>

5. Aggressive Scanning

Performing advanced scan including OS detection and script scanning.

nmap -A <IP_ADDRESS>

6. Host Discovery / Network Discovery

Checking active devices in a network.

nmap -sn <IP_ADDRESS>

7. TCP SYN Stealth Scan

Performing a stealthy TCP SYN scan.

nmap -sS <IP_ADDRESS>

8. Operating System Detection

Identifying the operating system of the target machine.

nmap -O <IP_ADDRESS>

9. NSE Basics

Using Nmap Scripting Engine for basic vulnerability scanning.

nmap --script vuln <IP_ADDRESS>

Skills Learned:

Port scanning
Service detection
Host discovery
OS detection
Basic vulnerability scanning
Networking fundamentals


Tools Used:

Nmap
Windows

