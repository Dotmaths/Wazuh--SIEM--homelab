# 🛡️ Wazuh SIEM Home Lab

## Project Overview
Built a Security Operations Center (SOC) home lab using 
Wazuh SIEM to detect and monitor cyber attacks in real time.

## Environment
- **SIEM:** Wazuh 4.x
- **Machines:** Wazuh Server (Linux), dotsec (Windows)
- **Network:** 192.168.1.0/24 (local VM environment)

## What I Did
- Deployed Wazuh server and enrolled a Windows agent
- Configured real-time file integrity monitoring (FIM)
- Reduced syscheck scan frequency from 12hrs to 5mins
- Simulated attacks using Atomic Red Team framework
- Detected and analyzed MITRE ATT&CK techniques

## Attacks Simulated
| Test | MITRE ID | Tactic | Detected? |
|------|----------|--------|-----------|
| Indicator Removal | T1070.001 | Defense Evasion | ✅ Yes |
| Command & Scripting | T1059.001 | Execution | ✅ Yes |

## Key Alerts Detected
- Registry Key Deletion (Rule 597)
- PowerShell Invoke-Command execution (Rule 91822, Level 12)
- Registry Integrity Checksum Changed (Rule 750)

## Skills Demonstrated
- SIEM deployment and configuration
- Threat detection and alert analysis
- Atomic Red Team attack simulation
- MITRE ATT&CK framework mapping
- Windows Registry forensics
- Incident response basics

## Screenshots

