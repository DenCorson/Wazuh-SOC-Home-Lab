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

## Project Documentation

| Part | Description | Status |
|------|-------------|--------|
| 📄 [Part 1](Part%201%20-%20Creating%20the%20Windows%2011%20Victim%20VM.pdf) | Creating the Windows 11 Victim VM | Complete |
| 📄 [Part 2](Part%202%20-%20Installing%20Sysmon%20Configuration%20on%20Windows%20Endpoint.pdf) | Sysmon Deployment | Complete |
| 📄 [Part 3](Part%203%20Wazuh%20Deployment%20and%20Agent%20Installation.pdf) | Wazuh Deployment & Agent Enrollment | Complete |
