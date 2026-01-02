# Snowflake Credential Compromise Campaign (2024)

## Overview

This repository contains a threat analysis report on the 2024 Snowflake credential
compromise incidents that affected multiple organisations across different sectors.

The campaign did **not** involve exploitation of a vulnerability in the Snowflake
platform. Instead, attackers gained unauthorised access by abusing **valid stolen
credentials** on Snowflake accounts that did not have multi-factor authentication
(MFA) enforced.

This project focuses on understanding how credential-based cloud compromises occur,
how attackers operate using legitimate access, and what detection and mitigation
measures are relevant from a SOC and blue team perspective.

## What This Project Covers

- Credential compromise as an initial access vector
- Abuse of valid accounts in cloud environments
- High-level attacker behaviour and access patterns
- Indicators of compromise (IOCs)
- Detection considerations for SOC teams
- Mitigation and hardening recommendations
- MITRE ATT&CK mapping

## Why This Matters

These incidents highlight that even secure cloud platforms can be compromised when
identity security controls are weak. Monitoring only failed logins is insufficient;
successful authentication events must also be analysed.

This report demonstrates practical threat analysis and incident investigation skills
relevant to SOC and cloud security roles.

## Sources

- Public Snowflake security advisories (2024)
- CrowdStrike cloud threat intelligence reporting
- Mandiant cloud incident response publications
- MITRE ATT&CK framework

## Disclaimer

This project is based on publicly available information and is intended for
educational and portfolio purposes only. No sensitive or proprietary data is
included.
