# 🕵️ Digital Forensics & Incident Response – Case: afifjukka@gmail.com

## Overview

This repository contains a Digital Forensics and Incident Response (DFIR) report related to the investigation of the email address `afifjukka@gmail.com`. The analysis was conducted using open-source intelligence (OSINT) tools and dark web scanning frameworks, with the goal of identifying potential exposure, threat actor connections, or suspicious online activity.

---

## 🎯 Case Focus

- **Primary Identifier**: `afifjukka@gmail.com`
- **Associated Aliases**: `vv887ex1ty`, `KoJo`
- **Mentioned Platform**: Pasteelo (uses anonymized unique IDs)
- **Tools Used**: See below

---

## 🧰 Tools Used

The following tools and techniques were used to collect and analyze the digital evidence:

| Tool/Source       | Purpose                                              |
|-------------------|------------------------------------------------------|
| 🕸️ **SpiderFoot**  | Automated OSINT scanning (domains, emails, dark web) |
| 🔍 **WHOIS**       | Domain ownership and registration data               |
| 📧 **Email Headers**| Analysis of linked or spoofed email trails          |
| 🌐 **Tor/Onion List Checks** | Detection of .onion services and pastes      |
| 🗃️ **Metadata Analysis** | File origin, timestamps, and structure         |
| 📓 **Manual Correlation** | Username matching, alias tracing, domain overlap |
| 🧾 **CSV Parsing** | Structured data review from SpiderFoot exports       |

These tools provided a strong foundation for uncovering ties between the target identity and suspicious infrastructure.

---

## 🔍 Key Findings

### 📁 .onion Domain Exposure
Over **400+ `.onion` domains** were detected during the scan process, indicating potential mentions or associations with:
- Pastebins
- Dark web marketplaces
- Command and control (C2) malware infrastructure

### 📧 Email Associations
21 related or alias emails surfaced, including:
- `mlevedahl@gmail.com`
- `jltobler@gmail.com`
- MIME-formatted relay addresses used in header spoofing or anonymized communication

### 🌐 Domains of Interest
Examples of domains tied to the subject:
- `pasteelo23czesvyd[...]onion`
- `www.adultism.com` (reputationally sensitive domain)
- Multiple auto-generated or malformed domains suggestive of obfuscation techniques

### 🧬 Usernames Detected
- `afifjukka` – Matches the email
- `vv887ex1ty` – Likely used for anonymous or dark web postings

---

## 📉 Risk Summary

| Indicator        | Value                | Risk Level | Notes                                    |
|------------------|----------------------|------------|------------------------------------------|
| Email            | afifjukka@gmail.com  | High       | Appears across multiple dark web scans   |
| .onion Domains   | 400+                 | Critical   | Tied to paste sites and malware infra    |
| Username         | vv887ex1ty           | Medium     | Likely used on Pasteelo                  |
| Associated Emails| 21+                  | Medium     | Possible data leaks or spoofing targets  |

---

## 📄 Report File

The full report is available in PDF format:  
➡️ `DFIR_Report_AfifJukka.pdf`

---

## 🧠 Disclaimer

This investigation is based on publicly accessible information and OSINT tools. No intrusive techniques were used. Findings suggest possible exposure but **do not confirm criminal or malicious activity** by the subject.

---

## 📬 Contact & Attribution

Investigation by: [Your Name or Team]  
Tools: SpiderFoot, WHOIS, Tor OSINT, CSV parsers, manual correlation  
Date: `May 2025`
