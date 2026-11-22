# Week 1 – Networking Fundamentals & Network Simulation Tools

**IT-SIMPLERA Solutions – Network Administration Internship Program**
**Intern:** Alishan Ahmed

## Overview
A simple star-topology LAN (3 PCs + 1 switch) built in both Cisco Packet Tracer and GNS3. Static IP addresses were assigned and connectivity was verified with the ping command.

## IP Plan
| Device | IP Address | Subnet Mask |
|---|---|---|
| PC1 | 192.168.1.10 | 255.255.255.0 |
| PC2 | 192.168.1.11 | 255.255.255.0 |
| PC3 | 192.168.1.12 | 255.255.255.0 |

## Tools Used
- Cisco Packet Tracer
- GNS3 (VPCS + Ethernet Switch)
- PuTTY / Solar-PuTTY

## Repository Contents
- `Report.pdf` – Week 1 report
- `Alishan Ahmed WEEK -1.pkt` – Cisco Packet Tracer file
- GNS3 project files
- Screenshots (topologies and ping results)

## Verification
From PC1, `ping 192.168.1.11` and `ping 192.168.1.12` succeeded in both Packet Tracer and GNS3 (0% packet loss).
