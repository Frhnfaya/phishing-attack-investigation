# phishing-attack-investigation

 Phishing Attack Investigation – Cybersecurity Case Study

## Overview
This project documents a real-world style phishing attack investigation conducted for educational and defensive cybersecurity purposes.

The objective was to analyze a suspicious email, identify malicious infrastructure, and map the attack using standard incident response methodologies.

---

## Objectives
- Analyze phishing email characteristics
- Identify malicious domains and IP addresses
- Perform OSINT-based threat intelligence
- Map attacker behavior using Cyber Kill Chain
- Document Indicators of Compromise (IOCs)

---

## Tools & Techniques
- curl
- HackerTarget API
- WHOIS lookup
- Reverse IP lookup
- DNS analysis
- OSINT
- Cyber Kill Chain Framework

---

## Investigation Workflow

1. Phishing email analysis
2. Header inspection
3. Malicious URL extraction
4. Domain & IP reputation checks
5. Reverse IP enumeration
6. Kill Chain mapping
7. IOC documentation
8. Final incident summary

---

## Key Findings

- Identified 20+ malicious domains hosted on the same IP range
- Confirmed phishing infrastructure
- Classified attack as: Credential Harvesting Campaign
- Collected attacker infrastructure patterns

---

## Kill Chain Mapping

| Stage | Description |
|------|------------|
| Reconnaissance | Target email selection |
| Weaponization | Fake login page |
| Delivery | Phishing email |
| Exploitation | User clicks link |
| Installation | Credential harvesting page |
| Command & Control | Data exfiltration |
| Actions on Objectives | Account takeover attempt |

---

## Indicators of Compromise (IOCs)

- Malicious domains
- Hosting IP addresses
- Phishing URLs
- Email headers

(All redacted for safety)

---

## Disclaimer
This project is for **educational and defensive purposes only**.  
No illegal activity was performed.  
No systems were attacked.

---

## Skills Demonstrated
- SOC analysis
- Threat intelligence
- Incident response
- OSINT
- Cyber Kill Chain
- Blue team methodology
