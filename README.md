# Incident Response - ICMP Flood DoS Attack Analysis (NIST CSF)

## Overview

This project presents a structured incident response analysis of an **ICMP Flood Denial of Service (DoS)** attack, using the **NIST Cybersecurity Framework (CSF)**.

The objective is to demonstrate practical skills in:

- Incident detection and analysis;
- Threat identification;
- Response and mitigation strategies;
- Security improvement planning.

## Incident Description

An abnormal surge in ICMP (ping) traffic was detected, leading to network congestion and service degradation.

- **Attack Type:** ICMP Flood (DoS);
- **Impact:** Service disruption and performance degradation;
- **Target:** Network infrastructure;
- **Severity:** High.

## Incident Timeline

| Time     | Event                                    |
| -------- | ---------------------------------------- |
| 10:00 AM | Unusual network activity detected        |
| 10:05 AM | Spike in ICMP traffic identified         |
| 10:10 AM | Network performance degradation observed |
| 10:15 AM | Incident declared and response initiated |

## Attack Vector Analysis

The attack consisted of a high volume of ICMP Echo Requests, overwhelming network resources.

Key characteristics:

- High packet rate
- Network saturation
- Potential distributed sources (botnet behavior)

## Indicators of Compromise (IOCs)

- Abnormal ICMP traffic spikes;
- Increased bandwidth usage;
- Multiple repeated requests from different IP addresses.

## NIST Cybersecurity Framework (CSF)

### Identify
- Asset inventory and risk awareness.
### Protect
- Firewall rules and traffic filtering policies.
### Detect
- Network monitoring and anomaly detection.
### Respond
- Traffic mitigation and incident handling procedures.
### Recover
- Service restoration and monitoring improvements.

## Lessons Learned

- Early detection is critical to reduce impact;
- Network monitoring must be continuously improved;
- Rate limiting helps mitigate volumetric attacks.

## Security Improvements Implemented

- ICMP rate limiting;
- Firewall hardening;
- Enhanced monitoring and alerting.

## Full Incident Report

The complete report with detailed analysis is available below:
[Download Full Report (PDF)](https://chatgpt.com/c/Incident_Report_ICMP_Flood.pdf)

## Skills Demonstrated

- Incident Response;
- Network Security Analysis;
- Threat Detection;
- NIST CSF Application;
- Cybersecurity Documentation.