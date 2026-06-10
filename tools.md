# 🛠️ Essential Tools

As you progress through the roadmap, you will need to learn these industry-standard tools. 
**Note:** Most of these come pre-installed on Kali Linux or Parrot OS.

---

## 🔍 Information Gathering & Scanning

*   **[Nmap](https://nmap.org/):** The undisputed king of network scanning. Used to discover hosts, open ports, and running services.
    *   *Usage:* `nmap -sC -sV -p- <IP>`
*   **[Gobuster](https://github.com/OJ/gobuster) / [Feroxbuster](https://github.com/epi052/feroxbuster):** Extremely fast tools for directory and file brute-forcing on web servers.
    *   *Usage:* `gobuster dir -u http://<IP> -w /path/to/wordlist.txt`

## 🕸️ Web Application Testing

*   **[Burp Suite Community Edition](https://portswigger.net/burp/communitydownload):** A web proxy used to intercept, inspect, and modify web traffic between your browser and the target server. 
    *   *Focus on:* Proxy, Repeater, and Decoder tabs.
*   **[FoxyProxy](https://getfoxyproxy.org/):** A browser extension that makes it easy to quickly switch your web traffic through Burp Suite.
*   **[Wappalyzer](https://www.wappalyzer.com/):** Browser extension to identify the technologies (frameworks, CMS, analytics) used on websites.

## 📡 Traffic Analysis

*   **[Wireshark](https://www.wireshark.org/):** A graphical network protocol analyzer. It lets you see exactly what is happening on your network at a microscopic level.
    *   *Great for:* Analyzing PCAP files in CTFs.

## 🔑 Password Cracking & Wordlists

*   **[Hashcat](https://hashcat.net/hashcat/):** The world's fastest password recovery tool. Uses your GPU to crack hashes.
*   **[John the Ripper](https://www.openwall.com/john/):** A popular CPU-based password cracker.
*   **[SecLists](https://github.com/danielmiessler/SecLists):** Not a tool, but the ultimate collection of multiple types of lists used during security assessments (passwords, usernames, payloads, web shells).
    *   *Famous wordlist:* `rockyou.txt`

## 💻 Exploitation & Post-Exploitation

*   **[Metasploit Framework](https://www.metasploit.com/):** A massive exploitation framework. It contains thousands of pre-written exploits for known vulnerabilities.
    *   *Usage:* `msfconsole`
*   **[Searchsploit](https://www.exploit-db.com/searchsploit):** A command-line search tool for Exploit-DB, allowing you to find exploits without going online.

## 📝 Note-Taking (Crucial!)

*   **[Obsidian](https://obsidian.md/):** A powerful, markdown-based knowledge base. Highly recommended for organizing your pentest notes.
*   **[Notion](https://www.notion.so/):** Great for cloud-based note-taking and tracking your progress.
*   **[CherryTree](https://www.giuspen.com/cherrytree/):** A classic hierarchical note-taking app popular among hackers.
