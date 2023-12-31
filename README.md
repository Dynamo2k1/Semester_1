# Remote Code Execution (RCE) Presentation

## Presenters
- Muhammad Fahad
- Rana Uzair Ahmad
- Muhammad Usman
- Ayesha Wajid

## What is RCE?
Remote Code Execution (RCE) is a vulnerability that allows an attacker to execute code on a target system remotely.

## Impacts of RCE
The impacts of RCE can be severe and include:
- Theft of sensitive data
- Privilege escalation
- Setting up a backdoor
- DDoS attacks
- Ransomware

## Causes of RCE
The causes of RCE can include:
- Software vulnerabilities
- Inadequate remote machine security
- Outdated software
- Weak/default user input passwords

## Finding and Exploiting RCE
### By Muhammad Usman
### Finding RCE Vulnerability
To find RCE vulnerabilities, you can:
- Perform manual testing
- Examine code for common vulnerabilities
- Monitor suspicious activity
- Understand the technology
- Perform a vulnerability scan

### Exploiting RCE Vulnerability
To exploit RCE vulnerabilities, you can use:
- Nmap for scanning the target IP
- Web scanning for backend language
- Burpsuite for sending requests and making malicious code
- Reverse shell

### By Rana Uzair Ahmad
### Exploitation Tools Usage
Tools Usage to Exploit the Vulnerability:
- Nmap for scanning any active IP address, performing entire network scanning, and identifying server's vulnerability
  - Use of Nmap: `sudo apt-get install nmap`
- Burpsuite

#### What is Burpsuite?
- Spider
- Proxy
- Intruder
- Repeater
- Sequencer
- Decoder
- Extender
- Scanner
- Burpsuite Example: Web Scanning Web Shell Access

## Patching and Prevention for RCE
### By Ayesha Wajid
### How to Patch the Vulnerability
To prevent RCE vulnerabilities, you can:
- Fix the extensions to prevent RCE vulnerability
- Update system and server
- Disable unnecessary services
- Always remain cautious
- Secure file uploading
- Least privileges
- Two-factor authentication
- Use firewall
- Disable remote access
