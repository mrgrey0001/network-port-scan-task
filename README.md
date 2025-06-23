#  🔍 Task 1: Local Network Port Scanning

## 🎯 Objective
To discover open ports on devices within the local network using Nmap and understand which services are potentially exposed, thereby learning the basics of network reconnaissance.


## 🛠 Tools Used
**Nmap** – For active network scanning  
**Wireshark** – For passive traffic capture and analysis


## 📝 Steps Followed

### 1. Installed Nmap
Used Kali Linux's pre-installed Nmap tool (Version: 7.95).

### 2. Identified Local IP Range
Used `ifconfig` to find IP:
### 3. Performed TCP SYN Scan Using Nmap
Used sudo nmap -sS 192.168.31.0/24 -oN scan-results.txt
Results were saved to scan-results.txt
### 4. Used Wireshark for Packet-Level Analysis
Opened Wireshark and selected wlan0 as the interface.
Started live capture before running the Nmap command.
