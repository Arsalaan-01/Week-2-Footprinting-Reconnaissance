# Week 2 – Footprinting & Reconnaissance

**Cybersecurity Internship | Networkwalks**

This repository documents my Week 2 practical work on Footprinting and Reconnaissance using Kali Linux.

## 🎯 Project Overview

The objective was to understand how publicly available information about a target domain can be collected and analyzed through passive and active reconnaissance techniques.

**Target Domain:** `networkwalks.com`

## 🛠️ Tools Used

- WHOIS – Domain registration information
- Nslookup – DNS queries
- DIG – DNS record enumeration
- WhatWeb – Website technology identification
- cURL – HTTP response and security headers
- DNSRecon – DNS enumeration
- WAFW00F – Web Application Firewall fingerprinting
- Traceroute – Network path analysis
- Subdomain enumeration – DNS-based discovery

## 📂 Repository Structure

```text
Week-2-Footprinting-Reconnaissance/
│
├── Screenshots/
│   ├── PM1_01_WHOIS.png
│   ├── PM1_02_NSLOOKUP.png
│   ├── PM1_03_DIG.png
│   └── ... 
│
├── Outputs/
│   ├── whois.txt
│   ├── nslookup.txt
│   ├── dig.txt
│   ├── dnsrecon.txt
│   ├── dns_summary.txt
│   ├── subdomain_enum.txt
│   └── ...
│
└── README.md
```

## 🔍 Key Activities

1. Domain information gathering using WHOIS.
2. DNS record enumeration (A, NS, MX, TXT and CNAME).
3. Subdomain discovery.
4. Website technology identification.
5. HTTP response and security-header inspection.
6. Network connectivity and traceroute analysis.
7. DNS reconnaissance using DNSRecon.
8. WAF fingerprinting attempts using WAFW00F.

## 📊 Observations

- Identified the target's IPv4 address: `192.232.216.135`.
- Identified HostGator nameservers.
- Retrieved MX and TXT records.
- Identified several subdomains, including mail, ftp, webmail and cpanel.
- DNSRecon identified 8 SRV records.
- WAFW00F encountered connection timeouts, so firewall identification remained inconclusive.

## 📸 Evidence

The `Screenshots` directory contains terminal screenshots documenting the practical exercises.

The `Outputs` directory contains the corresponding command outputs and collected reconnaissance data.

## 📚 Learning Outcomes

- Understanding passive and active reconnaissance.
- Working with DNS records and domain infrastructure.
- Using Kali Linux reconnaissance tools.
- Interpreting network and HTTP information.
- Organizing technical findings and documenting practical work.

## ⚠️ Disclaimer

This repository is intended for educational purposes as part of my cybersecurity internship. Reconnaissance activities should only be conducted against systems for which appropriate authorization has been obtained.

---

**Author:** Dar Arsalan  
**Program:** Cybersecurity Internship – Networkwalks  
**Week:** 02 – Footprinting & Reconnaissance
