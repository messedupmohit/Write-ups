# Slingshot – Blue Team SIEM Log Investigation (TryHackMe)

## Overview

This project documents a blue team investigation conducted on a compromised e-commerce web server using Elastic Stack logs. Acting as a SOC Analyst, I analysed web server activity to identify attacker behaviour, compromised accounts, exploited vulnerabilities, and data exfiltration.

The investigation is based on the TryHackMe **Slingshot** room and focuses on real-world SOC workflows such as log analysis, IOC identification, timeline reconstruction, and incident reporting.

## Scenario

Slingway Inc., a toy company, detected suspicious activity on its e-commerce infrastructure. Elastic Stack logs were provided to investigate a suspected attack that occurred on **26 July 2023**.

The objective was to reconstruct the attack timeline and answer key incident response questions:

- How did the attacker gain access?
- What tools and techniques were used?
- What data was compromised?

## Skills Demonstrated

- SIEM log analysis (Elastic / Kibana)
- Web attack investigation
- Threat hunting using IOCs
- Incident timeline reconstruction
- Blue team reporting and documentation
- SOC analyst decision-making

## Tools Used

- Elastic Stack (Kibana)
- KQL (Kibana Query Language)
- TryHackMe AttackBox
- CyberChef (for decoding credentials)

## Investigation Highlights

- Identified attacker IP and scanning activity
- Detected directory enumeration and brute-force attempts
- Confirmed credential compromise
- Tracked web shell deployment and command execution
- Observed database access and data exfiltration

## Key Findings

- Attacker IP: `10.0.2.15`
- Compromised admin credentials
- Web shell uploaded and executed
- Sensitive database exported

## Documentation

- Full incident report: **Incident_Report.md**
- Screenshots: `/screenshots` directory (Elastic queries, results, findings)

## Disclaimer

This project is for educational and portfolio purposes only. All data is simulated and sourced from a controlled lab environment.
