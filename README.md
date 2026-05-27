# Network Reconnaissance Using Nmap

## Overview

This project demonstrates practical network reconnaissance and vulnerability assessment using:

- Nmap
- Metasploit Framework
- Nessus Essentials

The project was performed inside a controlled cybersecurity lab environment using Kali Linux. Multiple services were configured locally to simulate a realistic target machine for reconnaissance and security analysis.

---

# Features

- Network reconnaissance
- Port scanning
- Service enumeration
- OS fingerprinting
- Aggressive scanning
- Metasploit integration
- Vulnerability assessment using Nessus
- Local cybersecurity lab setup

---

# Technologies Used

- Kali Linux
- Nmap
- Metasploit Framework
- Nessus Essentials
- Apache2
- OpenSSH
- Netcat
- VMware

---

# Lab Environment

The following services were configured locally:

| Port | Service |
|---|---|
| 22 | SSH |
| 80 | Apache HTTP Server |
| 8080 | Python HTTP Server |
| 4444 | Netcat Listener |
| 9999 | Netcat Listener |

---

# Important Nmap Commands

## Basic Scan

```bash
nmap 127.0.0.1
```

## Service Version Detection

```bash
sudo nmap -sV 127.0.0.1
```

## OS Detection

```bash
sudo nmap -O 127.0.0.1
```

## Aggressive Scan

```bash
sudo nmap -A 127.0.0.1
```

---

# Metasploit Integration

## Start Metasploit

```bash
msfconsole
```

## Verify Database

```bash
db_status
```

## Run Nmap Inside Metasploit

```bash
db_nmap 127.0.0.1
```

## View Hosts

```bash
hosts
```

## View Services

```bash
services
```

---

# Nessus Vulnerability Assessment

Nessus Essentials was used to perform vulnerability assessment on localhost.

The scan identified:
- Apache HTTP findings
- SSH related findings
- SSL/TLS observations
- Service detection information
- Python library vulnerability observations

---

# Screenshots

## Apache Server
<img width="885" height="495" alt="image" src="https://github.com/user-attachments/assets/c68ae294-e486-4062-b565-f3195f5bcb29" />

---

## Nmap Service Detection
<img width="900" height="572" alt="image" src="https://github.com/user-attachments/assets/b5e622d8-6c40-4cbc-8bd0-d6dba58e9c3c" />

---

## Metasploit Services Enumeration
<img width="900" height="863" alt="image" src="https://github.com/user-attachments/assets/1dabd60c-63c0-4b55-b98a-ed53bbe0b545" />

---

## Nessus Vulnerability Results
<img width="900" height="351" alt="image" src="https://github.com/user-attachments/assets/6dd59c38-807a-4554-9b20-06b49d27d1fe" />

---

# Learning Outcomes

Through this project, the following concepts were learned:

- Practical network reconnaissance
- Service enumeration
- Vulnerability assessment
- Penetration testing workflow
- Metasploit and Nmap integration
- Cybersecurity lab setup and configuration

---

# Future Improvements

- Add Metasploitable 2 integration
- Create automated reporting system
- Develop GUI-based scanner
- Integrate Wireshark packet analysis
- Add real-time dashboard

---

# Disclaimer

This project was developed in a controlled local lab environment for educational and ethical purposes only.

---

# Author
**Prkhar Sharma**  
B.Tech CSE (Cyber Security)  
Bennett University
