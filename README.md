# Week 2: Scanning & Footprinting Task

## ⚠️ Legal Disclaimer
All activities were performed on personally owned or explicitly authorized systems for educational and research purposes only.

---

## 📌 Overview
This repository contains my Week 2 assignment for the NetworkWalks Cybersecurity Internship.
It covers domain reconnaissance and local network discovery

---

## 🛠️ Tools Used
* **Kali Linux:** Platform used for running domain footprinting commands
* **WHOIS:** Retrieved domain registration details like registrar, creation/expiry dates, and name servers
* **WhatWeb:** Identified web technologies such as WordPress 7.1.4 and Apache server
* **NSLookup:** Resolved the target domain name to its IP address.
* **Curl (-I):** Inspected HTTP response headers, server type, and security cookies
* **Wafw00f:** Detected that the website is protected behind a ModSecurity Web Application Firewall
* **DNSRecon:** Enumerated DNS records including NS, MX, TXT, and SRV records
* **Zenmap (Nmap GUI):** Performed a ping scan on the local subnet (`192.168.0.0/24`) to find live hosts
* **Windows CMD:** Used `ipconfig` to check local IP and subnet configuration

---

## 🔍 Key Findings Summary
* **Domain Footprinting (`networkwalks.com`):** Registered via GoDaddy, hosted on an Apache server (`192.232.216.135`), runs WordPress 7.1.4, and uses a ModSecurity WAF
* **Local Network Scanning (`192.168.0.0/24`):** Scanned 256 IP addresses and discovered **5 live hosts** (Default gateway, three mobile devices, and my Windows PC)

---

## 👩‍💻 Author
* **Name:** Shazma Sitara
* **Program:** NetworkWalks Cybersecurity Internship (Batch B084M)
