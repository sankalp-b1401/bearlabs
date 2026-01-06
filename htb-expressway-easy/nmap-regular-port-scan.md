## Nmap Regular Scan

**Command:** `nmap -sV 10.10.11.87 -T4`

Starting Nmap 7.98 ( https://nmap.org ) at 2026-01-06 03:00 -0500
NSE: Loaded 48 scripts for scanning.
Initiating Ping Scan at 03:00
Scanning 10.10.11.87 [4 ports]
Completed Ping Scan at 03:00, 0.36s elapsed (1 total hosts)
**Initiating SYN Stealth Scan** at 03:00
**Scanning expressway.htb (10.10.11.87) [1000 ports]**
Discovered open port 22/tcp on 10.10.11.87
Completed SYN Stealth Scan at 03:00, 4.39s elapsed (1000 total ports)
Initiating Service scan at 03:00
Scanning 1 service on expressway.htb (10.10.11.87)
Completed Service scan at 03:00, 0.70s elapsed (1 service on 1 host)
NSE: Script scanning 10.10.11.87.
Initiating NSE at 03:00
Completed NSE at 03:00, 0.00s elapsed
Initiating NSE at 03:00
Completed NSE at 03:00, 0.00s elapsed
Nmap scan report for expressway.htb (10.10.11.87)
Host is up (0.64s latency).
Not shown: 999 closed tcp ports (reset)
**PORT STATE SERVICE VERSION
22/tcp open ssh OpenSSH 10.0p2 Debian 8 (protocol 2.0)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel**

Read data files from: /usr/share/nmap
Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 6.03 seconds
Raw packets sent: 1110 (48.816KB) | Rcvd: 1110 (44.392KB)
