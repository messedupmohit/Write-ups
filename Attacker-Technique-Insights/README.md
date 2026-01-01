# Brute Force Heroes – Defensive Analysis

## Overview

This repository documents a hands-on security analysis performed using the _Brute Force Heroes_ room on **TryHackMe**. The objective was to understand brute-force attack techniques from an attacker’s perspective and translate those observations into defensive detection and prevention strategies.

The work is presented strictly from a Blue Team / SOC viewpoint.

## Platform

- Training Environment: TryHackMe
- Room Name: Brute Force Heroes
- Lab Type: Simulated and authorised environment

## Purpose

The goal of this project is to:

- Understand how brute-force attacks are executed
- Identify behavioural patterns attackers generate
- Recognise detection opportunities within logs and network traffic
- Improve defensive monitoring and response strategies

## Activities Performed

The lab covered brute-force attacks across multiple vectors, including:

- Web application authentication brute forcing
- SSH brute force attacks
- Credential encoding and reuse
- Offline hash brute forcing

Multiple tools were used to observe how attackers adapt tooling based on service behaviour and defensive controls.

## Defensive Focus

Rather than focusing on exploitation, this project emphasises:

- What indicators defenders would see
- How brute-force attempts differ across protocols
- Why certain tools succeed where others fail
- How misconfigurations increase attack success

## Report

A detailed defensive analysis is provided in `REPORT.txt`, covering:

- Attacker behaviour
- Detection indicators
- Defensive controls
- SOC-relevant recommendations

## Disclaimer

All activities were conducted in a controlled lab environment for educational purposes only. No real systems or unauthorised targets were involved.
