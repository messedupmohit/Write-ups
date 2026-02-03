# Friday Overtime – Cyber Threat Intelligence Investigation (TryHackMe)

## 📖 Overview

This repository documents a **Cyber Threat Intelligence (CTI) investigation**
completed as part of the TryHackMe room **Friday Overtime**.

The scenario places the analyst in a real-world CTI workflow, responding to a
ticket involving suspicious malware samples submitted by an external source.
The objective is not exploitation, but **analysis, enrichment, and reporting**
of threat intelligence in a safe and structured manner.

This project focuses on **how defenders think**, rather than how attackers break in.

---

## 🎯 Objectives

- Analyse malware artefacts provided in an investigation ticket
- Extract and verify file hashes
- Use OSINT sources to identify malware families and behaviour
- Map observed capabilities to MITRE ATT&CK techniques
- Safely defang malicious URLs and IP addresses
- Produce actionable Indicators of Compromise (IOCs)
- Document findings in a CTI-style investigation report

---

## 🧪 Investigation Context

- **Platform:** TryHackMe
- **Room:** Friday Overtime
- **Role Simulated:** Cyber Threat Intelligence Analyst
- **Environment:** Controlled lab
- **Tools & Resources Used:**
  - Terminal (hashing and file inspection)
  - VirusTotal
  - CyberChef
  - Open-source threat intelligence reports
  - MITRE ATT&CK framework

---

## 🔍 What This Investigation Covers

- Identification of a malicious DLL and hash verification
- Enrichment of malware artefacts using OSINT
- Malware framework identification (e.g. backdoor modules)
- Behavioural mapping to MITRE ATT&CK techniques
- Safe handling of malicious infrastructure (URLs and IPs)
- Correlation of additional malware hosted on the same infrastructure

---

## 🧠 Skills Demonstrated

- Cyber Threat Intelligence analysis
- Malware artefact triage
- IOC extraction and defanging
- ATT&CK technique mapping
- Analytical thinking and contextual research
- SOC / CTI-style documentation

---

## 📂 Repository Structure

Friday-Overtime-CTI/
├── README.md
├── report.txt
└── screenshots/
├── 01_sender_identified.png
├── 02_prsm_dll_hash.png
├── 03_malware_framework.png
├── 04_mitre_attack_mapping.png
├── 05_defanged_url.png
├── 06_defanged_ip.png
└── 07_related_malware.png

Each screenshot corresponds to a specific investigation step and is referenced
directly within the report.

---

## 📘 Key Takeaway

Rooms like **Friday Overtime** reinforce that effective blue team work is not
about running tools in isolation, but about **adding context** — understanding
what an artefact is, why it matters, and how it fits into a broader threat
landscape.

---

## ⚠️ Disclaimer

This investigation was conducted in a **controlled lab environment** for
educational and portfolio purposes only. No real systems were harmed.


