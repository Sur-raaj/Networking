# Network Commands for Testing & Troubleshooting

## 📌 Overview
This repository contains documentation and practical examples of commonly used **network commands** in the Windows operating system.  
The purpose is to provide hands-on experience with diagnostic tools that help in testing connectivity, analyzing routes, and troubleshooting network issues.

---

## 🎯 Objectives
- Explore and understand commonly used network commands for connectivity testing and troubleshooting.
- Observe and analyze the output of diagnostic commands in Windows CMD.
- Develop practical skills in identifying and resolving common network problems.
- Gain hands-on experience in verifying network configurations and ensuring reliable communication.

---

## 📖 Theory
Network commands are essential tools for:
- Detecting connectivity problems
- Checking IP configurations
- Identifying routing errors
- Resolving communication failures

In Windows, these commands are executed via **Command Prompt (CMD)**.  
Key commands include:
- `ping` → Test connectivity
- `tracert` → Trace packet routes
- `ipconfig` → View IP configuration
- `nslookup` → DNS queries
- `netstat` → Monitor active connections
- `pathping` → Analyze packet loss
- `route` → Display/modify routing tables
- `arp` → Show ARP table
- `hostname` → Display system name
- `getmac` → Show MAC addresses
- `nbtstat` → NetBIOS info

---


## 🚀 How to Use
1. Open **Command Prompt (CMD)** in Windows.
2. Run the commands listed above.
3. Compare your outputs with the examples in `Network Commands.pdf`.
4. Use these tools to troubleshoot real-world network issues.

---

## 📑 Quick Reference Cheatsheet
- `ping` → Test connectivity  
- `tracert` → Trace route hops  
- `ipconfig` → Show IP details  
- `nslookup` → DNS lookup  
- `netstat -a` → Active connections  
- `pathping` → Connectivity + packet loss  
- `route print` → Routing table  
- `arp -a` → ARP table  
- `hostname` → System name  
- `getmac` → MAC addresses  
- `nbtstat` → NetBIOS info

---
## 🛠 Commands & Usage

| Command   | Syntax / Example | Purpose |
|-----------|------------------|---------|
| **Ping** | `ping <hostname>` | Test connectivity with ICMP echo requests |
| **Tracert** | `tracert <hostname>` | Trace route packets take to destination |
| **Ipconfig** | `ipconfig` / `ipconfig /all` | Display IP configuration details |
| **Nslookup** | `nslookup <hostname>` | Query DNS servers for domain/IP mapping |
| **Netstat** | `netstat -a` | Show active TCP/UDP connections and listening ports |
| **Pathping** | `pathping <hostname>` | Analyze connectivity + packet loss across hops |
| **Route** | `route print` / `route add <dest> mask <mask> <gateway>` | Display/modify routing table |
| **Arp** | `arp -a` | Show ARP table (IP ↔ MAC mapping) |
| **Hostname** | `hostname` | Display computer’s name on the network |
| **Getmac** | `getmac` | Show MAC addresses of adapters |
| **Nbtstat** | `nbtstat -n` / `nbtstat -s` | Display NetBIOS info (names, sessions) |

---

## 💡 Discussion
By practicing these commands, we learned how to:
- Verify communication between devices (`ping`, `tracert`)
- Check IP configurations (`ipconfig`)
- Resolve DNS issues (`nslookup`)
- Monitor connections (`netstat`)
- Analyze packet loss (`pathping`)
- Inspect routing and ARP tables (`route`, `arp`)
- Identify system/network details (`hostname`, `getmac`, `nbtstat`)

---

## ✅ Conclusion
This lab demonstrated the importance of **basic network commands** in diagnosing and resolving connectivity problems.  
Through practical exposure, we strengthened our understanding of network operations and built confidence in using command-line tools for troubleshooting.



