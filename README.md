# Networkwalks-Week-2
Cybersecurity Internship
# Week 2 — Footprinting & Network Scanning

Completed Week 2 of my Cybersecurity & Ethical Hacking internship at Networkwalks.

## 🔍 Footprinting (Kali Linux)

Used six tools — WHOIS, WhatWeb, Nslookup, Curl (-I), Wafw00f, and DNSRecon — to perform reconnaissance on a target domain.

**Key findings:**

| Tool | Finding |
|------|---------|
| WhatWeb | Identified WordPress 7.0.4 and WP Download Manager 3.3.58 |
| Nslookup | Resolved domain to IP address |
| Curl -I | Revealed HTTP response headers and exposed the `/wp-json/` WordPress REST API endpoint |
| Wafw00f | Detected ModSecurity (SpiderLabs) as the active WAF |
| DNSRecon | Enumerated name servers, mail servers, SPF/TXT records, and service records |

## 🖥️ Network Scanning (Zenmap)

Identified local IP and MAC address via Command Prompt, then used Zenmap (Nmap GUI) to scan the local subnet — discovering live hosts, their IP/MAC addresses, and generating a network topology diagram.

## 📄 Deliverable

Wrote a complete pentesting-style report covering methodology, tool-by-tool findings, risk analysis, and remediation recommendations.

---

**Tools used:** `WHOIS` `WhatWeb` `Nslookup` `Curl` `Wafw00f` `DNSRecon` `Zenmap`



https://github.com/reehamalik70-beep/Networkwalks-Week-2/blob/93f767b8597423ca196fbe3f8eb65ff4befab9aa/whois%20results.JPG


https://github.com/reehamalik70-beep/Networkwalks-Week-2/blob/67a562493595eb0896b90f9e0b62d2b83145e208/whois%20results%202.JPG

https://github.com/reehamalik70-beep/Networkwalks-Week-2/blob/52916908f69ea23f9c75e589db4859d622c4520c/whois%20reults%203.JPG



https://github.com/reehamalik70-beep/Networkwalks-Week-2/blob/e6458ef516a865ca1e9a54bbaa2f166d27a05766/whatweb%20outcom.JPG

https://github.com/reehamalik70-beep/Networkwalks-Week-2/blob/758034151b8907e237269d3120faad9eda96e8e6/curl%20-I%20outcome.JPG

https://github.com/reehamalik70-beep/Networkwalks-Week-2/blob/74e51587e285505c3b9cd3a07930b2ce253f70eb/dnsrecon%20-d%20iutcome.JPG

https://github.com/reehamalik70-beep/Networkwalks-Week-2/blob/2b401432d90aa3708cddea95c59a7d974f16c336/nslookup%20outcome.JPG

https://github.com/reehamalik70-beep/Networkwalks-Week-2/blob/c4688f03788ff5d4ab5c67080c4dce3a91a2a389/wafw00f%20outcome.JPG
