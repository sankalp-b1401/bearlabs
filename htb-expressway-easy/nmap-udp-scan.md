## Nmap UDP Scan

**Command:** `nmap -sU 10.10.11.87 -T4 -v`

Starting Nmap 7.98 ( https://nmap.org ) at 2026-01-06 03:05 -0500
Starting Nmap 7.98 ( https://nmap.org ) at 2026-01-06 03:05 -0500
Initiating Ping Scan at 03:05
Scanning 10.10.11.87 [4 ports]
Completed Ping Scan at 03:05, 0.35s elapsed (1 total hosts)
Initiating UDP Scan at 03:05
Scanning expressway.htb (10.10.11.87) [1000 ports]
Increasing send delay for 10.10.11.87 from 0 to 50 due to 11 out of 18 dropped probes since last increase.
Increasing send delay for 10.10.11.87 from 50 to 100 due to max_successful_tryno increase to 5
Increasing send delay for 10.10.11.87 from 100 to 200 due to max_successful_tryno increase to 6
Warning: 10.10.11.87 giving up on port because retransmission cap hit (6).
UDP Scan Timing: About 4.67% done; ETC: 03:16 (0:10:33 remaining)
Increasing send delay for 10.10.11.87 from 200 to 400 due to 11 out of 13 dropped probes since last increase.
Increasing send delay for 10.10.11.87 from 400 to 800 due to 11 out of 17 dropped probes since last increase.
UDP Scan Timing: About 7.87% done; ETC: 03:18 (0:11:54 remaining)
UDP Scan Timing: About 12.56% done; ETC: 03:19 (0:12:39 remaining)
UDP Scan Timing: About 23.03% done; ETC: 03:20 (0:11:55 remaining)
UDP Scan Timing: About 29.16% done; ETC: 03:21 (0:11:06 remaining)
UDP Scan Timing: About 34.84% done; ETC: 03:21 (0:10:19 remaining)
Discovered open port 500/udp on 10.10.11.87
UDP Scan Timing: About 40.34% done; ETC: 03:21 (0:09:29 remaining)
UDP Scan Timing: About 46.37% done; ETC: 03:21 (0:08:38 remaining)
UDP Scan Timing: About 51.70% done; ETC: 03:21 (0:07:49 remaining)
UDP Scan Timing: About 56.86% done; ETC: 03:21 (0:07:00 remaining)
UDP Scan Timing: About 62.39% done; ETC: 03:21 (0:06:08 remaining)
UDP Scan Timing: About 67.56% done; ETC: 03:21 (0:05:17 remaining)
UDP Scan Timing: About 72.84% done; ETC: 03:21 (0:04:27 remaining)
UDP Scan Timing: About 77.93% done; ETC: 03:21 (0:03:37 remaining)
UDP Scan Timing: About 82.99% done; ETC: 03:21 (0:02:48 remaining)
UDP Scan Timing: About 87.99% done; ETC: 03:21 (0:01:59 remaining)
UDP Scan Timing: About 93.00% done; ETC: 03:21 (0:01:09 remaining)
Completed UDP Scan at 03:22, 1035.94s elapsed (1000 total ports)
Nmap scan report for expressway.htb (10.10.11.87)
Host is up (0.66s latency).
Not shown: 995 closed udp ports (port-unreach)
**PORT STATE SERVICE
68/udp open|filtered dhcpc
69/udp open|filtered tftp
500/udp open isakmp
4500/udp open|filtered nat-t-ike**
49157/udp open|filtered unknown

Read data files from: /usr/share/nmap
Nmap done: 1 IP address (1 host up) scanned in 1036.47 seconds
Raw packets sent: 1470 (68.576KB) | Rcvd: 32445 (1.338MB)
