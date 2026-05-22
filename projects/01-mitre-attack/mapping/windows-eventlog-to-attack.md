# Windows Event Log to MITRE ATT&CK Mapping

## Purpose

Map common Windows Event IDs to possible MITRE ATT&CK tactics and techniques.

| Event ID | Meaning | Possible ATT&CK Tactic | Notes |
|---|---|---|---|
| 4624 | Successful logon | Initial Access / Lateral Movement | Check logon type |
| 4625 | Failed logon | Credential Access | Possible brute force |
| 4634 | Logoff | Investigation Context | Session ended |
| 4647 | User initiated logoff | Investigation Context | User manually logged off |
| 4688 | Process creation | Execution | Check suspicious command line |
| 1102 | Audit log cleared | Defense Evasion | Possible log clearing |
| 7045 | Service installed | Persistence / Privilege Escalation | Suspicious service creation |
