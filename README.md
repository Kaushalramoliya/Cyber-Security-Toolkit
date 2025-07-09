# 🛡️ Cyber Security Toolkit

This repository contains a series of practical Cyber Security Lab Assignments implemented on a Windows 10/11 system, covering a wide range of security domains such as network diagnostics, packet analysis, digital forensics, scanning, firewalls, and password cracking using tools like Wireshark, Angry IP Scanner, Nmap, Recuva, Autopsy Sleuthkit, John the Ripper, and various online vulnerability scanners.

---

## 📋 Index

| Sr. No. | Assignment Title                          | Tool(s)/Technology Used                   |
|---------|-------------------------------------------|-------------------------------------------|
| 1       | Diagnostic and Troubleshooting TCP/IP Commands | Windows CMD/PowerShell                    |
| 2       | Network Analysis using Wireshark          | Wireshark                                 |
| 3       | Scanning using Angry IP Scanner           | Angry IP Scanner                          |
| 4       | Advanced Scanning using Nmap              | Nmap                                      |
| 5       | Digital Forensics using Recuva            | Recuva                                    |
| 6       | Digital Forensics using Autopsy Sleuthkit | Autopsy Sleuthkit                         |
| 7       | Blocking URLs with Windows Firewall       | Windows Defender Firewall                 |
| 8       | Password Cracking using John the Ripper   | John the Ripper (Ubuntu/Kali Linux)       |
| 9       | Website Vulnerability Assessment using Online Tools | Pentest-tools.com, Immuniweb.com          |

---

## 💻 Requirements

Ensure you have the following installed or accessible:

* **Windows 10 or 11**
* **Internet connection**
* **Admin rights** (for installations)
* **VirtualBox** (Optional for sandboxing tools)
* **Tools** mentioned in each assignment section

---

## 🔧 Tools & Technologies Used

* **CMD / PowerShell** – Basic TCP/IP diagnostics
* **Wireshark** – Live network packet capture
* **Angry IP Scanner** – IP/host discovery
* **Nmap** – Network scanning, OS detection, service enumeration
* **Recuva** – File recovery utility
* **Autopsy Sleuthkit** – Digital forensic tool
* **John the Ripper** – Password cracking
* **Online Tools** – Web vulnerability scanners
* **Windows Firewall** – URL blocking rules

---

## 🚀 Assignment Implementation

Each assignment contains step-by-step implementation along with screenshots as evidence.

### ✅ Assignment 1: TCP/IP Command Line Tools

* `ipconfig /all` to extract IP, Gateway, DNS, MAC, etc.
* `ping`, `tracert`, `nslookup` for reachability checks
* Continuous ping: `ping -t www.bata.com`
* Reverse DNS: `nslookup 27.123.43.205`
* Custom packet size and hop limits

### ✅ Assignment 2: Wireshark Packet Capture

* Install **Wireshark** and select appropriate NIC
* Use `icmp` filter for ping traffic
* Apply filters: `icmp`, `http`, etc.
* Capture ICMP traffic using `ping` command
* Demonstration of HTTP password visibility (non-HTTPS)

### ✅ Assignment 3: Angry IP Scanner

* Scan local network using Hotspot
* Validate live hosts using IP
* Host Apache server and detect ports
* Compare scanner output with `ipconfig`

### ✅ Assignment 4: Nmap Scanning

Perform:

* Ping scan: `nmap -sn 192.168.0.1/24`
* TCP scan: `nmap -sT`
* Stealth scan: `nmap -sS`
* UDP scan: `nmap -sU`
* OS Detection: `nmap -O`
* Use `scanme.nmap.org` for testing

### ✅ Assignment 5: Recuva File Recovery

* Delete image/doc files and recover via **Recuva**
* Use deep scan option
* Recover from multiple locations
* Use File Shredder and test if recovery is still possible

### ✅ Assignment 6: Autopsy Sleuthkit

* Detect files with fake extensions (e.g., `.jpg.exe`)
* Perform keyword search for IP addresses, URLs, and emails

### ✅ Assignment 7: Windows Firewall

* Block specific URLs via outbound rules
* Demonstrate using screenshots

### ✅ Assignment 8: John the Ripper

* Install in Ubuntu: `sudo apt install john`
* Run using:
    * Single Crack: `john --single password.txt`
    * Wordlist: `john --wordlist=rockyou.txt password.txt`
    * Incremental: `john --incremental password.txt`

### ✅ Assignment 9: Online Vulnerability Scanners

* Scan same URL set using:
    * `https://pentest-tools.com/website-vulnerability-scanning/website-scanner`
    * `https://www.immuniweb.com/websec/`
* Report common vs uncommon vulnerabilities

---

## 📁 Folder Structure (on GitHub)

```bash
Cyber-Security-Lab/
├── Assignment-1_TCPIP_Commands.pdf
├── Assignment-2_Wireshark.pdf
├── Assignment-3_Angry_IP.pdf
├── Assignment-4_Nmap.pdf
├── Assignment-5_Recuva.pdf
├── Assignment-6_Autopsy.pdf
├── Assignment-7_Firewall.pdf
├── Assignment-8_John_Ripper.pdf
├── Assignment-9_Vulnerability_Scanner.pdf
├── cyber security.pdf
└── README.md
```

---

## 🙋 About Me

> 👨‍💻 **Kaushal Ramoliya**  
> 🎓 B.Tech in Computer Science & Engineering  
> 📧 Email: [kaushalramoliya17@gmail.com](mailto:kaushalramoliya17@gmail.com)  
> 🌐 LinkedIn: [linkedin.com/in/kaushalramoliya](https://www.linkedin.com/in/kaushalramoliya)  
> 💻 GitHub: [github.com/kaushalramoliya](https://github.com/Kaushalramoliya)
