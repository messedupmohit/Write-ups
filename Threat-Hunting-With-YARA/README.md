# Threat Hunting With YARA — TryHackMe Write-Up

## Overview

This repository contains a SOC-style investigation of the **TryHackMe Threat Hunting With YARA** challenge.  
The goal of this room was to learn how to define and use **YARA rules** to hunt for malicious artifacts in a dataset.

The investigation included writing a custom YARA rule to detect a given string pattern, applying it to a dataset, and interpreting the results to answer challenge questions.

---

## What This Repository Contains

- `report.txt` — Incident report with findings and answers
- `screenshots/` — Evidence screenshots referenced in the report (e.g., `01_…`, `02_…`, etc.)

---

## Skills Demonstrated

- Writing and testing YARA rules
- Threat hunting workflow
- SIEM-style documentation and artifact extraction
- Mapping detection logic to findings

---

## Tools Used

- YARA
- Threat dataset provided in the room
- CLI tools (grep/cat/etc.)
