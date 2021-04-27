Vendor: BeyondTrust
===================
Product: BeyondTrust
--------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  65   |   31   |     8      |      4      |    4    |

|                                  Use-Case                                  | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | MITRE TTP                                                                                                                                                                                                | Content                                                                                                                      |
|:--------------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  account-switch<br> ↳ [s-liebsoft-account-switch](Parsers/parserContent_s-liebsoft-account-switch.md)<br> ↳ [syslog-liebsoft-account-switch-1](Parsers/parserContent_syslog-liebsoft-account-switch-1.md)<br><br> app-activity<br> ↳ [beyondtrust-pi-password-access](Parsers/parserContent_beyondtrust-pi-password-access.md)<br><br> app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br><br> failed-app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br> | T1003 - OS Credential Dumping<br>T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1133 - External Remote Services<br> | [<ul><li>47 Rules</li></ul><ul><li>25 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  account-switch<br> ↳ [s-liebsoft-account-switch](Parsers/parserContent_s-liebsoft-account-switch.md)<br> ↳ [syslog-liebsoft-account-switch-1](Parsers/parserContent_syslog-liebsoft-account-switch-1.md)<br><br> app-activity<br> ↳ [beyondtrust-pi-password-access](Parsers/parserContent_beyondtrust-pi-password-access.md)<br><br> app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br><br> failed-app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1114.003 - Email Collection: Email Forwarding Rule<br>                                                                         | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_Data_Exfiltration.md)         |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          |  account-switch<br> ↳ [s-liebsoft-account-switch](Parsers/parserContent_s-liebsoft-account-switch.md)<br> ↳ [syslog-liebsoft-account-switch-1](Parsers/parserContent_syslog-liebsoft-account-switch-1.md)<br><br> app-activity<br> ↳ [beyondtrust-pi-password-access](Parsers/parserContent_beyondtrust-pi-password-access.md)<br><br> app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br><br> failed-app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                               | [<ul><li>13 Rules</li></ul><ul><li>9 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_Internal_Fraud.md)           |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  account-switch<br> ↳ [s-liebsoft-account-switch](Parsers/parserContent_s-liebsoft-account-switch.md)<br> ↳ [syslog-liebsoft-account-switch-1](Parsers/parserContent_syslog-liebsoft-account-switch-1.md)<br><br> app-activity<br> ↳ [beyondtrust-pi-password-access](Parsers/parserContent_beyondtrust-pi-password-access.md)<br><br> app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br><br> failed-app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                                                                           | [<ul><li>7 Rules</li></ul><ul><li>5 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_Lateral_Movement.md)          |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       |  account-switch<br> ↳ [s-liebsoft-account-switch](Parsers/parserContent_s-liebsoft-account-switch.md)<br> ↳ [syslog-liebsoft-account-switch-1](Parsers/parserContent_syslog-liebsoft-account-switch-1.md)<br><br> app-activity<br> ↳ [beyondtrust-pi-password-access](Parsers/parserContent_beyondtrust-pi-password-access.md)<br><br> app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br><br> failed-app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>                                                                                                               | [<ul><li>10 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_Malware_Detection.md)        |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  account-switch<br> ↳ [s-liebsoft-account-switch](Parsers/parserContent_s-liebsoft-account-switch.md)<br> ↳ [syslog-liebsoft-account-switch-1](Parsers/parserContent_syslog-liebsoft-account-switch-1.md)<br><br> app-activity<br> ↳ [beyondtrust-pi-password-access](Parsers/parserContent_beyondtrust-pi-password-access.md)<br><br> app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br><br> failed-app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                                                                                                      | [<ul><li>7 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_Privileged_Activity.md)       |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    |  account-switch<br> ↳ [s-liebsoft-account-switch](Parsers/parserContent_s-liebsoft-account-switch.md)<br> ↳ [syslog-liebsoft-account-switch-1](Parsers/parserContent_syslog-liebsoft-account-switch-1.md)<br><br> app-activity<br> ↳ [beyondtrust-pi-password-access](Parsers/parserContent_beyondtrust-pi-password-access.md)<br><br> app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br><br> failed-app-login<br> ↳ [beyondtrust-pi-app-login](Parsers/parserContent_beyondtrust-pi-app-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>                                                                                                               | [<ul><li>10 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_Ransomware_Detection.md)     |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access                                                          | Discovery | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> |           |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |