## Nmap Scan for all Ports

**Command:** `nmap -sV -p- 10.10.11.87 -T4`

Starting Nmap 7.98 ( https://nmap.org ) at 2026-01-06 03:06 -0500
NSE: Loaded 48 scripts for scanning.
Initiating Ping Scan at 03:06
Scanning 10.10.11.87 [4 ports]
Completed Ping Scan at 03:06, 0.54s elapsed (1 total hosts)
Initiating **SYN Stealth Scan** at 03:06
**Scanning expressway.htb (10.10.11.87) [65535 ports]**
Discovered open port 22/tcp on 10.10.11.87
SYN Stealth Scan Timing: About 6.27% done; ETC: 03:14 (0:07:44 remaining)
Increasing send delay for 10.10.11.87 from 0 to 5 due to 1541 out of 3852 dropped probes since last increase.
Increasing send delay for 10.10.11.87 from 5 to 10 due to 11 out of 21 dropped probes since last increase.
SYN Stealth Scan Timing: About 7.04% done; ETC: 03:20 (0:13:25 remaining)
SYN Stealth Scan Timing: About 7.79% done; ETC: 03:25 (0:17:57 remaining)
SYN Stealth Scan Timing: About 8.51% done; ETC: 03:29 (0:21:40 remaining)
SYN Stealth Scan Timing: About 9.20% done; ETC: 03:33 (0:24:50 remaining)
SYN Stealth Scan Timing: About 12.16% done; ETC: 03:32 (0:23:14 remaining)
SYN Stealth Scan Timing: About 15.17% done; ETC: 03:31 (0:21:55 remaining)
SYN Stealth Scan Timing: About 41.48% done; ETC: 03:41 (0:20:33 remaining)
SYN Stealth Scan Timing: About 47.63% done; ETC: 03:41 (0:18:43 remaining)
SYN Stealth Scan Timing: About 54.14% done; ETC: 03:42 (0:16:55 remaining)
SYN Stealth Scan Timing: About 59.43% done; ETC: 03:43 (0:15:04 remaining)
SYN Stealth Scan Timing: About 64.75% done; ETC: 03:43 (0:13:11 remaining)
SYN Stealth Scan Timing: About 70.31% done; ETC: 03:44 (0:11:17 remaining)
SYN Stealth Scan Timing: About 75.76% done; ETC: 03:44 (0:09:22 remaining)
SYN Stealth Scan Timing: About 81.04% done; ETC: 03:45 (0:07:25 remaining)
SYN Stealth Scan Timing: About 86.72% done; ETC: 03:46 (0:05:26 remaining)
SYN Stealth Scan Timing: About 91.91% done; ETC: 03:47 (0:03:23 remaining)
SYN Stealth Scan Timing: About 96.95% done; ETC: 03:48 (0:01:17 remaining)
Completed SYN Stealth Scan at 03:49, 2592.49s elapsed (65535 total ports)
Initiating Service scan at 03:49
Scanning 1 service on expressway.htb (10.10.11.87)
Completed Service scan at 03:49, 0.96s elapsed (1 service on 1 host)
NSE: Script scanning 10.10.11.87.
Initiating NSE at 03:49
Completed NSE at 03:49, 0.03s elapsed
Initiating NSE at 03:49
Completed NSE at 03:49, 0.02s elapsed
Nmap scan report for expressway.htb (10.10.11.87)
Host is up (0.94s latency).
Not shown: 65534 closed tcp ports (reset)
**PORT STATE SERVICE VERSION
22/tcp open ssh OpenSSH 10.0p2 Debian 8 (protocol 2.0)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel**

Read data files from: /usr/share/nmap
Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 2594.86 seconds
Raw packets sent: 72711 (3.199MB) | Rcvd: 70946 (2.877MB)
