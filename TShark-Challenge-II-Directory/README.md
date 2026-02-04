# TShark Challenge II: Directory

## Overview

This repository contains a SOC-style analysis write-up for **TryHackMe – TShark Challenge II: Directory**, a network forensic challenge requiring packet inspection and artifact extraction using **TShark**.

In this investigation, we examined the `directory-curiosity.pcap` capture to determine if a triggered alert was a true positive. The analysis included DNS inspection, HTTP request counting, object extraction, file hashing, and threat intelligence lookup.

---

## What This Repository Contains

- `report.txt` — Blue Team-structured incident report with findings and analysis
- `screenshots/` — referenced screenshots numbered sequentially (e.g., `01_…`, `02_…`)

---

## Skills Demonstrated

- DNS and HTTP analysis with TShark
- Identifying suspicious domains and resolving associated IPs
- File object extraction from PCAP
- Computing file hashes and threat intelligence enrichment
- Documenting findings like a SOC analyst

---

## Tools Used

- TShark
- Linux CLI
- VirusTotal
