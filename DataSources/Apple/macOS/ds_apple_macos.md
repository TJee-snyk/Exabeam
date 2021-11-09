Vendor: Apple
=============
Product: macOS
--------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  41   |   19   |     5      |      1      |    1    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> | T1078 - Valid Accounts<br>T1078.003 - Valid Accounts: Local Accounts<br> | [<ul><li>22 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_apple_macos_Abnormal_Authentication_&_Access.md) |
|    [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)    |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_apple_macos_Brute_Force_Attack.md)    |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> | T1078.002 - T1078.002<br>T1558 - Steal or Forge Kerberos Tickets<br>     | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_apple_macos_Compromised_Credentials.md)    |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> | T1558 - Steal or Forge Kerberos Tickets<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_apple_macos_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> | T1204 - User Execution<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_apple_macos_Malware.md)    |
|    [Other](../../../UseCases/uc_other.md)    |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> |    | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_apple_macos_Other.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> | T1078 - Valid Accounts<br>T1078.002 - T1078.002<br>    | [<ul><li>10 Rules</li></ul><ul><li>6 Models</li></ul>](RM/r_m_apple_macos_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_apple_macos_Privilege_Escalation.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  local-logon<br> ↳[osx-local-logon](Ps/pC_osxlocallogon.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>6 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_apple_macos_Privileged_Activity.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                                                                                                            | Credential Access                                                                    | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Valid Accounts: Local Accounts](https://attack.mitre.org/techniques/T1078/003)<br><br> | [Steal or Forge Kerberos Tickets](https://attack.mitre.org/techniques/T1558)<br><br> |           |                  |            |                     |              |        |