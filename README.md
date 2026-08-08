# Network Reconnaissance and Security Assessment

## Overview

This project presents a controlled network reconnaissance and security assessment performed in an isolated virtual laboratory environment.

Kali Linux was used as the security assessment machine and Ubuntu Server was configured as the target system. The assessment focused on identifying active hosts, exposed ports and services, operating system information, and network communication patterns.

## Objective

Assess the security posture of a controlled lab network through network reconnaissance and packet analysis.

## Scope

- Host discovery and network mapping
- Port and service enumeration
- OS fingerprinting
- Identification of exposed services and associated risks
- Packet analysis

## Tools Used

- Kali Linux
- Nmap
- Netdiscover
- Wireshark
- Oracle VirtualBox

## Lab Environment

| System | Role | Network |
|---|---|---|
| Kali Linux | Assessment Machine | 192.168.56.0/24 |
| Ubuntu Server | Target | 192.168.56.0/24 |

## Key Findings

- Active hosts were identified using Netdiscover and Nmap.
- Ubuntu Server was identified as the target system.
- TCP port 22 was found open.
- OpenSSH 10.2p1 was detected.
- SSH Protocol Version 2.0 was observed.
- ARP, ICMP, TCP, and SSH traffic were analyzed using Wireshark.
- No critical security issues were identified within the defined project scope.

## Risk Summary

The target presented a limited attack surface because only the SSH service was exposed.

The primary security consideration was the exposed SSH service, which should be protected through strong authentication, regular updates, and appropriate access controls.

## Deliverables

- Network topology diagram
- Scan results
- Security findings
- Risk analysis
- Recommendations
- Practical commands and screenshots
- Complete project report

## Repository Structure

```text
Commands/                                   → Commands used during assessment
Findings_Risk_Analysis_recommendation/      → Findings and risk analysis summary and recommendations
Report/                                     → Final project report
Screenshots/                                → Practical evidence
Topology/                                   → Network topology diagram
