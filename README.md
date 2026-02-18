# Web Infrastructure Attack Detection & Automated Containment

## Project Overview
This project demonstrates detection, automated containment, and remediation of a real-world web server compromise in Microsoft Azure.

An intentionally vulnerable web server was attacked, monitored using Microsoft Sentinel, and automatically defended using Azure Logic Apps and Network Security Groups.

## Key Capabilities
- Simulated web server compromise and attacker activity
- Real-time attack detection using Microsoft Sentinel
- Automated incident response to block malicious IPs
- Dynamic NSG rule creation to contain attackers
- Security dashboards for attack visibility
- Vulnerability remediation and server hardening

## Technologies Used
- Microsoft Azure VM
- Microsoft Sentinel
- Azure Logic Apps
- Network Security Groups (NSG)
- Log Analytics Workspace
- Apache Web Server (Linux)

## Workflow
1. Vulnerable web server deployed
2. Attacker exploited server
3. Logs collected and analyzed
4. Sentinel detected malicious behavior
5. Logic App blocked attacker IP automatically
6. Vulnerability fixed and services hardened
7. Dashboard created for monitoring

## Screenshots
See `/screenshots` folder for attack detection, automation, dashboard, and remediation proof.

