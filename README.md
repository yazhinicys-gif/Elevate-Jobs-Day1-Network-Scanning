# Elevate-Jobs-Day1-Network-Scanning
Day 1 Cybersecurity Internship Task - Local Network Scanning using Nmap.
# Local Network Scanning Using Nmap

## Task 1: Scan Your Local Network for Open Ports

### Objective
To identify active devices and open ports in a local network using Nmap.

### Tools Used
- Nmap 7.99
- Windows PowerShell
- GitHub

### Steps Performed
1. Installed Nmap on Windows.
2. Identified the local network device.
3. Performed a TCP SYN scan.
4. Identified open TCP ports and their services.
5. Saved the scan output in a text file.

### Scan Results

Target IP: 192.168.29.218

| Port | Service |
|---|---|
| 135 | MSRPC |
| 139 | NetBIOS-SSN |
| 445 | Microsoft-DS |
| 16992 | AMT-SOAP-HTTP |

### Security Observations
- Open ports should be checked and secured.
- Unnecessary services should be disabled.
- Firewalls should restrict unauthorized access.
- Systems should be regularly updated.

### Learning Outcome
Learned the basics of Nmap, port scanning, TCP SYN scans, network services and network security.

### Disclaimer
Scanning was performed on an authorized device/network.
