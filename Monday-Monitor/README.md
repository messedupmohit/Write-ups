# Monday Monitor — TryHackMe Write-Up

## Overview

This repository contains a SOC-style incident report for the **TryHackMe Monday Monitor** challenge, focused on endpoint log analysis using Wazuh and Sysmon.

In this exercise, we investigated simulated malicious activity on a Windows host to identify suspicious processes, persistence mechanisms, credential dumping, and exfiltration. The analysis was guided by a saved query in the Wazuh dashboard to filter relevant events.

---

## What’s Included

- `report.txt` — Detailed incident report with executive findings
- `screenshots/` — Image evidence referenced in sequence

---

## Skills Demonstrated

- SIEM log investigation (Wazuh)
- Process execution and command-line analysis
- Base64 decoding for payload inspection
- Extraction of persistence and credential dumping artifacts
- Writing SOC-style detection and analysis documentation

---

## Tools Used

- Wazuh SIEM Dashboard
- Sysmon log event analysis
- Base64 decoding tools (e.g., CyberChef)
