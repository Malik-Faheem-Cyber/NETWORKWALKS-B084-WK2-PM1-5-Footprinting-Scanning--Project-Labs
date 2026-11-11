# Footprinting, Reconnaissance & Network Host Discovery

**Cybersecurity Internship – Networkwalks | Week 02**

## Project Overview

This repository documents the practical cybersecurity activities completed during Week 02 of my Cybersecurity Internship at Networkwalks.

The work covers two practical areas: website footprinting and reconnaissance, followed by network scanning and host discovery within a personal virtual lab environment.

## Objectives

- Collect publicly available information about a website.
- Identify web technologies and domain infrastructure.
- Examine HTTP response headers and detect WAF technology.
- Enumerate available DNS records.
- Discover active hosts within a controlled virtual lab network.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Security testing environment |
| WHOIS | Domain registration information |
| WhatWeb | Web technology identification |
| Nslookup | DNS resolution |
| cURL | HTTP response header inspection |
| Wafw00f | Web Application Firewall detection |
| DNSRecon | DNS record enumeration |
| Zenmap / Nmap | Network host discovery |
| Linux Terminal | Network configuration using ifconfig |

## Activities Performed

### 1. Footprinting & Reconnaissance

Performed authorized reconnaissance of the assigned website, `networkwalks.com`, using Kali Linux tools.

The activities included:

- Domain registration information gathering.
- Web server, CMS, and plugin identification.
- Domain-to-IP resolution.
- HTTP response header inspection.
- Web Application Firewall identification.
- DNS record enumeration.

### 2. Network Scanning & Host Discovery

Performed network discovery within my own virtual lab environment.

- Identified the local network configuration using `ifconfig`.
- Used Zenmap with the Nmap Ping Scan option.
- Scanned the local `/24` network range.
- Identified two active hosts: `10.0.0.1` and `10.0.0.2`.

The activity was limited to host discovery. No port scanning, service enumeration, or exploitation was performed.

## Key Observations

- Website technologies and domain infrastructure were identified.
- ModSecurity (SpiderLabs) was detected by Wafw00f.
- DNSRecon identified eight DNS records.
- Zenmap discovered two active hosts in the virtual lab.

These observations represent information gathered during the exercises and do not establish confirmed exploitable vulnerabilities.

## Repository Contents

- `report/` – Week 02 practical report, including supporting screenshots.
- `topology/` – Virtual lab host-discovery topology diagram.

## Scope & Disclaimer

Website reconnaissance was conducted within the authorized internship scope. Network discovery was restricted to my own virtual lab environment.

This project is intended for educational and professional learning purposes. No exploitation or unauthorized access was performed.

**Note:** Website assessment details and supporting evidence are shared publicly only subject to the relevant organization's approval.
