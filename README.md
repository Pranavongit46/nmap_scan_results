# 🛡️ Nmap Scan Results – Local Network Enumeration

This repository contains the results of a port and service scan on the local network using **Nmap**. The goal was to identify live hosts, open ports, and exposed services to assess potential security risks.

---

## 🔧 Tools Used

- [Nmap](https://nmap.org) v7.95
- Kali Linux (Virtual Machine)
- Basic networking utilities (`ip`, `python3`, etc.)

---

## 📡 Network Details

- **Subnet Scanned**: `192.168.62.0/24`
- **Live Hosts Identified**:
  - `192.168.62.1`
  - `192.168.62.2`
  - `192.168.62.254`

---

## 🔍 Scan Techniques

### 1. Discover Live Hosts
```bash
nmap -sn 192.168.62.0/24
