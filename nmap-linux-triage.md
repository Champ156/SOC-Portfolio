# Nmap Recon + Linux Log Analysis
**Kali Linux 

## Attacker Reconnaissance (Detected)

nmap -sV scanme.nmap.org

![Nmap Live Scan](nmap-scanme.png)[file:357]

**Open Services:**
- Port 22/ssh: OpenSSH 6.6.1p1 (brute force target)  
- Port 80/http: Apache 2.4.7 (Ubuntu)
- Port 443/https: Apache (TLS)

## SOC Server Triage

*sudo tail -20 /var/log/auth.log | grep “Failed”
*sudo tail -20 /var/log/auth.log | grep sshd

![Linux Log Troubleshooting](auth-log-troubleshoot.png)

**Production Finding:**

## SOC Response


**Skills Demonstrated:**
Nmap -sV scanning + Linux log troubleshooting + SOC triage

<img width="1920" height="1080" alt="Screenshot 2026-02-24 at 9 47 16 AM" src="https://github.com/user-attachments/assets/d74cffeb-38f8-4b29-88cf-8cb0e477f85d" />
