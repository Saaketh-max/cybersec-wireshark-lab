# 🛡️ Wireshark Protocol Analysis Report

**Analyst:** D.V.S. Saaketh  
**Date:** 29 September 2025  
**Interface Used:** enp0s3 (VirtualBox NAT)

## 🔍 Summary
Captured 1 minute of traffic while pinging and browsing websites.

### 📡 Protocols Identified
- **DNS** – Resolving domain names
- **TCP** – Reliable transport layer for HTTP
- **ICMP** – Ping requests and replies

### 📦 Sample Packet Details
1. **DNS Query**
   - Src: 10.0.2.15 → Dst: 8.8.8.8
   - Port: 5353 → 53
   - Info: Query for example.com

2. **TCP Segment**
   - Src: 10.0.2.15 → Dst: 93.184.216.34
   - Port: 443
   - Info: HTTP GET /index.html

3. **ICMP Echo Request**
   - Src: 10.0.2.15 → Dst: 93.184.216.34
   - Info: Ping request

## 📁 Export
- Raw capture: `capture_report.pcap`
- Summary: `summary.md`
