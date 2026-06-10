# 🗺️ Detailed 6-Month Roadmap

This is your week-by-week guide. Stick to the schedule, but don't rush. If a topic takes longer, that's okay!

---

## 🟢 Month 1: Foundations (IT, Networking & Linux)
*Goal: Understand how computers talk to each other and how to use the command line.*

* **Week 1: Networking Basics I**
  * OSI Model & TCP/IP suite
  * IP Addressing (IPv4 vs IPv6) & Subnetting basics
  * MAC Addresses & ARP
* **Week 2: Networking Basics II**
  * Common Ports & Protocols (HTTP/S, FTP, SSH, DNS, DHCP)
  * How DNS works
  * The HTTP Request/Response cycle
* **Week 3: Linux Fundamentals**
  * Navigating the file system (`cd`, `ls`, `pwd`)
  * File permissions (`chmod`, `chown`)
  * Package management (`apt`)
  * *Lab: Play OverTheWire Bandit levels 0-15.*
* **Week 4: Virtualization**
  * What are Virtual Machines (VMs)?
  * Install VirtualBox or VMware Player.
  * Install Kali Linux or Parrot OS in a VM.

---

## 🟡 Month 2: Coding & Scripting Basics
*Goal: Learn to read code and write automation scripts.*

* **Week 1: Python Basics**
  * Variables, Data Types, Loops, Conditionals
  * Functions and Modules
  * *Resource: freeCodeCamp Python course.*
* **Week 2: Python for Security**
  * File I/O (reading/writing text files)
  * Working with the `requests` library to make HTTP calls.
  * *Project: Build a basic port scanner in Python.*
* **Week 3: Bash Scripting**
  * Automating Linux commands
  * Variables and loops in Bash
  * *Project: Write a Bash script to automate system updates.*
* **Week 4: Web Fundamentals**
  * Read basic HTML and CSS
  * Understand JavaScript basics (DOM manipulation)
  * Understand REST APIs and JSON

---

## 🟠 Month 3: Security Fundamentals
*Goal: Learn the theory of security, cryptography, and risk.*

* **Week 1: Core Concepts**
  * The CIA Triad (Confidentiality, Integrity, Availability)
  * Authentication vs. Authorization
  * Principle of Least Privilege
* **Week 2: Cryptography Basics**
  * Hashing (MD5, SHA-256) vs. Encryption
  * Symmetric vs. Asymmetric Encryption (AES vs. RSA)
  * Public Key Infrastructure (PKI) and Digital Certificates
* **Week 3: Threat Modeling & Risk**
  * Identifying assets and threats
  * STRIDE threat model
  * Vulnerability vs. Exploit vs. Payload
* **Week 4: Vulnerability Assessment**
  * What is a CVE? (Common Vulnerabilities and Exposures)
  * CVSS Scoring system
  * Using vulnerability databases (NVD, Exploit-DB)

---

## 🔴 Month 4: Web Application Security
*Goal: Understand how web applications are hacked.*

* **Week 1: Introduction to OWASP & Injection**
  * Explore the OWASP Top 10
  * SQL Injection (SQLi): How it works and how to test for it.
  * Command Injection.
* **Week 2: Cross-Site Scripting (XSS)**
  * Reflected XSS
  * Stored XSS
  * DOM-based XSS
  * *Lab: PortSwigger XSS Labs.*
* **Week 3: Broken Authentication & Session Management**
  * Cookie manipulation
  * JWT (JSON Web Token) basics
  * Privilege Escalation (IDOR/BOLA)
* **Week 4: CSRF & SSRF**
  * Cross-Site Request Forgery (CSRF)
  * Server-Side Request Forgery (SSRF)
  * *Lab: PortSwigger CSRF/SSRF Labs.*

---

## 🟣 Month 5: Tools of the Trade & Exploitation
*Goal: Master the essential software hackers use every day.*

* **Week 1: Nmap (Network Mapper)**
  * Host discovery (`-sn`)
  * Port scanning (`-sS`, `-sT`)
  * Version detection (`-sV`) and OS detection (`-O`)
  * Nmap Scripting Engine (NSE)
* **Week 2: Web Proxies (Burp Suite)**
  * Setting up Burp Suite with your browser (FoxyProxy)
  * Using the Proxy and Repeater tabs
  * Intruder basics for brute-forcing
* **Week 3: Traffic Analysis (Wireshark)**
  * Capturing packets
  * Filtering traffic (e.g., `http`, `tcp.port==80`)
  * Following TCP streams
* **Week 4: Enumeration & Initial Access**
  * Directory busting (Gobuster / Feroxbuster)
  * Finding public exploits (Searchsploit)
  * Understanding Reverse Shells vs. Bind Shells

---

## ⚫ Month 6: Practice, Projects, & Professional Polish
*Goal: Prove your skills, build a portfolio, and prepare for jobs.*

* **Week 1: CTF Practice**
  * Complete 3-5 rooms on TryHackMe (e.g., Blue, Ice, Basic Pentesting)
  * Practice writing a simple "Writeup" for one of the rooms.
* **Week 2: Penetration Testing Methodology**
  * Learn the PTES (Penetration Testing Execution Standard)
  * Phases: Recon, Scanning, Exploitation, Post-Exploitation, Reporting
* **Week 3: The Capstone Project**
  * Perform a full simulated penetration test in a lab environment.
  * Write a professional Penetration Testing Report.
  * *(See [projects.md](./projects.md) for details).*
* **Week 4: Resume & Interview Prep**
  * Add your labs, scripts, and Capstone Project to your resume.
  * Create a GitHub profile showcasing your scripts.
  * Review common SOC/Pentester interview questions.
