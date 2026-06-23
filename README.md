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
-  Executing test: T1070-1 Indicator Removal using FSUtil
<img width="1269" height="256" alt="image" src="https://github.com/user-attachments/assets/cc2864a5-654c-4d25-a092-227ebf9b450d" />


-  PowerShell Attack Caught
<img width="1280" height="975" alt="image" src="https://github.com/user-attachments/assets/b5861e0a-18b0-4d6a-9646-dc544ffbc3e0" />


- Executing cleanup for test
<img width="1255" height="336" alt="image" src="https://github.com/user-attachments/assets/2f916534-a43c-44b7-b45b-a00c4f51fc49" />


- Alert Dashboard
<img width="1280" height="984" alt="image" src="https://github.com/user-attachments/assets/eef49086-c08c-456a-ad4f-25239166ce74" />

