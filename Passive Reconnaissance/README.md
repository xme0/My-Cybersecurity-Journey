# Passive Reconnaissance

## What is Passive Reconnaissance?
**Passive Reconnaissance** is the process of collecting information about a target without directly interacting with its systems. It relies on publicly accessible sources and tools, making it stealthy and difficult to detect.

---

## What Kind of Data is Collected?

1. **Publicly Accessible Information:**
   - Email addresses, phone numbers, IP addresses, domain names  
   - Social media profiles, geographic locations, suppliers  
   - Deployed technologies, hosting providers

2. **Technical Stack & System Info:**
   - Operating systems, software, programming languages  
   - Technologies used on websites (e.g., CMS, web servers)

---

## Common Tools for Passive Recon

| Tool | Description |
|------|-------------|
| [**Google Dorking**](https://github.com/chr3st5an/Google-Dorking) | Crafting custom Google queries to uncover hidden files, directories, passwords, etc. |
| [**Censys**](https://search.censys.io/) | Search engine for internet-connected devices. |
| [**Shodan.io**](https://www.shodan.io/) | Search engine for finding public devices based on filters like port, OS, etc. |
| **Email Headers** | Reveal sender IP, server information, and routing details. |
| [**Cookie Editor Extensions**](#what-you-can-learn-with-cookie-editors) | Analyze session cookies and authentication details (read-only use = passive). |
| [**Whois**](https://labex.io/tutorials/linux-linux-whois-command-with-practical-examples-423010) | Retrieves domain owner details, registrar info, contact, and registration dates. |
| [**Wappalyzer**](https://www.wappalyzer.com/) | Detects technology stack used by websites. |
| [**ImmuniWeb Security Test**](https://www.linkedin.com/pulse/day-88-immuniweb-community-edition-comprehensive-free-soumya-swarup-sa4jc/) | Scans websites/APIs for vulnerabilities and compliance (passively). |
| **DNS Tools**: [nslookup](https://cheat.sh/nslookup), [dig](https://cheat.sh/dig), [DNSDumpster](https://dnsdumpster.com/) | Gather DNS records, MX, TXT, and IP ranges. |
| [**theHarvester**](https://www.cheat-sheets.org/project/tldr/command/theharvester/) | Collects emails, subdomains, and IPs from public sources. |
| [**Maltego**](https://medium.com/@whart842/maltego-reference-guide-584bed1384a8) | Link analysis and OSINT visualization tool. |
| [**Recon-ng**](https://hackertarget.com/recon-ng-tutorial/) | Recon framework that automates collection from many public sources. |
| [**OSINT Framework**](https://osintframework.com/) | A curated directory of OSINT tools categorized by data type. |
| [**Wayback Machine**](https://web.archive.org/) | View old versions of websites and discover historical data. |
| [**Netcraft**](https://searchdns.netcraft.com/) | Maps infrastructure and finds subdomains and server locations. |
| [**Wireshark**](https://hackertarget.com/wireshark-tutorial-and-cheat-sheet/) | If network access is gained (e.g., public Wi-Fi), can analyze traffic for intelligence. *(Passive only if eavesdropping, not injecting)* |

---

## What You Can Learn with Cookie Editors

Using extensions like **EditThisCookie** or **Cookie-Editor**, you can passively analyze:

- **Session & Tracking Cookies:**
  - Technologies used (JWTs, Google Analytics, etc.)

- **Authentication Mechanisms:**
  - Discover token formats and cookie flags (Secure, HttpOnly, SameSite)

- **Server-Side Behavior:**
  - Observe if cookies are persistent, encrypted, or regenerated

> **Note:** Modifying cookies becomes *active reconnaissance*
