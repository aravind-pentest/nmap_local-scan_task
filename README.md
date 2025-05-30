# nmap_local-scan_task

## Task Objective
Perform a TCP SYN scan on the local network to discover open ports and understand network exposure.

## Steps Taken
1. Installed Nmap on Kali Linux.
2. Identified local IP range: 192.168.1.0/24.
3. Ran TCP SYN scan with `nmap -sS 192.168.1.0/24 -oN local_scan.txt`.
4. Analyzed scan results and noted open ports and active hosts.
5. Ran full port scan on own IP with `nmap -p- 192.168.1.55 -oN full_self_scan.txt`.
6. Researched common services on detected ports.

## Commands Used
```bash
nmap -sS 192.168.1.0/24 -oN local_scan.txt
nmap -p- 192.168.1.55 -oN full_self_scan.txt
