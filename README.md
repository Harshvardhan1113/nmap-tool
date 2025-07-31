# nmap-tool
# 🔍 Network Vulnerability Assessment using Nmap (Aggressive Scan)

This repository contains a hands-on vulnerability assessment project conducted in a virtual lab environment. The assessment used **Nmap** with the aggressive scan (`-A`) option to discover live hosts, enumerate open ports and services, detect OS versions, and identify potential vulnerabilities.


## Lab Environment

- **Tool Used**: [Nmap](https://nmap.org/) (with `-A` flag)
- **Platform**: Kali Linux
- **Hosts Scanned**: 4 Virtual Machines
- **Scope**: Local subnet scanning (192.168.X.X/24) and manual enumeration of specific hosts.


## Nmap Scan Overview

Nmap aggressive scan includes:
- OS detection
- Version detection
- Script scanning
- Traceroute

Example command:
```bash
nmap -A 192.168.X.0/24

