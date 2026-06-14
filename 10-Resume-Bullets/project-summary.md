# Project Summary

This project demonstrates a Windows endpoint detection and threat hunting lab using Wazuh and Sysmon.

The environment collects Windows telemetry from endpoint agents and forwards logs to a centralized Wazuh SIEM server for analysis, alerting, and visualization.

Attack simulations were performed to validate detections for:
- PowerShell activity
- User account creation
- Executable drops
- Discovery commands

The project includes:
- Wazuh server deployment
- Windows agent integration
- Sysmon telemetry collection
- Threat hunting dashboards
- MITRE ATT&CK aligned detections