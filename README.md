# Wazuh SOC Home Lab

## Overview

This project documents the design, deployment, troubleshooting, and operation of a Windows security monitoring lab using Wazuh SIEM. The environment simulates an enterprise network where endpoint telemetry is collected, analyzed, and investigated using industry-standard security tools.

---

## Objectives

- Deploy a Wazuh Manager on Ubuntu Server
- Configure a Windows 11 endpoint with Sysmon
- Install and enroll the Wazuh Agent
- Centralize Windows security telemetry
- Generate simulated attacks from Kali Linux
- Investigate alerts using Wazuh
- Document the deployment and troubleshooting process

---

## Technologies

- Wazuh SIEM
- Ubuntu Server
- Windows 11 Enterprise
- Kali Linux
- Sysmon
- Oracle VirtualBox
- PowerShell

---

## Lab Architecture

Ubuntu Server (Wazuh Manager)
            │
            │
    Windows 11 Endpoint
      (Sysmon + Wazuh Agent)
            ▲
            │
     Kali Linux Attacker

---

## Project Documentation

| Part | Description | Status |
 Part 1 | Lab Planning 
 Part 2 | Sysmon Deployment 
 Part 3 | Wazuh Deployment & Agent Enrollment 
 Part 4  Security Event Analysis 

---

## Skills Demonstrated

- SIEM Deployment
- Endpoint Security Monitoring
- Windows Event Analysis
- Linux Administration
- PowerShell
- Sysmon Configuration
- Wazuh Agent Deployment
- Security Documentation
- Troubleshooting
