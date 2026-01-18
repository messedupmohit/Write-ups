# Dynamic Application Security Testing (DAST) – TryHackMe Write-Up

## 📖 Overview

This repository contains a **practical exploration of Dynamic Application Security Testing (DAST)** — a black-box approach to discovering vulnerabilities in _running_ web applications.

Instead of looking at code, DAST interacts with the application during execution, simulating real-world attacks to uncover runtime weaknesses. :contentReference[oaicite:6]{index=6}

This write-up is based on the TryHackMe DAST walkthrough and demonstrates key steps in dynamic scanning, authenticated probing, and vulnerability detection.

---

## 🧠 What You’ll Learn

- What DAST is and how it differs from static analysis
- How to spider and map an app dynamically
- How to configure a scan policy for relevance
- How authenticated scans discover deeper vulnerabilities
- How to interpret scanner findings

---

## 📂 Repository Structure

DAST/
├── README.md
├── report.txt
└── screenshots/
├── 01_spidering_map.png
├── 02_ajax_spider_results.png
├── 03_scan_policy_setup.png
├── 04_dast_active_scan.png
├── 05_authenticated_scan_setup.png
└── 06_vulnerability_results.png

Each screenshot represents a key phase in the DAST workflow documented in the report.

---

## 📘 Skills Demonstrated

- Application vulnerability scanning
- Black-box testing methodology
- Logged-in scanning
- Dynamic attack surface analysis
- Translation of scan results into defensive insights

---

## ⚠️ Disclaimer

This is an educational exploration performed in a controlled environment. The write-up is intended for learning purposes only.
