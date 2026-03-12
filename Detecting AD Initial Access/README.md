# Detecting AD Initial Access – Investigation Challenge (Task 08)

## Overview

This investigation was conducted as part of the **TryHackMe: Detecting AD Initial Access** room.

The scenario simulates a **SOC investigation** where an alert was triggered due to an abnormal number of **HTTP 404 responses from a single external IP** targeting an IIS web server.

The goal of the investigation was to determine:

- How the attacker gained access
- Whether a web shell was deployed
- What commands were executed on the compromised system

---

# Investigation Environment

SIEM Platform: Splunk  
Log Sources:

- IIS Access Logs → `index=iis`
- Windows Security / Sysmon Logs → `index=win`

---

# Investigation Steps

## 1. Detect Suspicious HTTP Activity

Initial investigation focused on identifying abnormal HTTP responses.

```spl
index=iis status=404
```
