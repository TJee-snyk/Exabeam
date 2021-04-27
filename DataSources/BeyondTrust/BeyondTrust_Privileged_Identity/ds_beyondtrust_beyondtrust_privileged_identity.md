Vendor: BeyondTrust
===================
Product: BeyondTrust Privileged Identity
----------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  54   |   27   |     6      |      2      |    2    |

|                                  Use-Case                                  | Event Types/Parsers                                                                                                                                                                                                                     | MITRE TTP                                                                                                                               | Content                                                                                                                                          |
|:--------------------------------------------------------------------------:| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳ [beyondtrust-pi-app-activity](Parsers/parserContent_beyondtrust-pi-app-activity.md)<br><br> privileged-access<br> ↳ [beyondtrust-pi-privilege-access](Parsers/parserContent_beyondtrust-pi-privilege-access.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1133 - External Remote Services<br> | [<ul><li>39 Rules</li></ul><ul><li>21 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_privileged_identity_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  app-activity<br> ↳ [beyondtrust-pi-app-activity](Parsers/parserContent_beyondtrust-pi-app-activity.md)<br><br> privileged-access<br> ↳ [beyondtrust-pi-privilege-access](Parsers/parserContent_beyondtrust-pi-privilege-access.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1114.003 - Email Collection: Email Forwarding Rule<br>        | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_privileged_identity_Data_Exfiltration.md)         |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          |  app-activity<br> ↳ [beyondtrust-pi-app-activity](Parsers/parserContent_beyondtrust-pi-app-activity.md)<br><br> privileged-access<br> ↳ [beyondtrust-pi-privilege-access](Parsers/parserContent_beyondtrust-pi-privilege-access.md)<br> | T1078 - Valid Accounts<br>                                                                                                              | [<ul><li>13 Rules</li></ul><ul><li>9 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_privileged_identity_Internal_Fraud.md)           |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  app-activity<br> ↳ [beyondtrust-pi-app-activity](Parsers/parserContent_beyondtrust-pi-app-activity.md)<br><br> privileged-access<br> ↳ [beyondtrust-pi-privilege-access](Parsers/parserContent_beyondtrust-pi-privilege-access.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                          | [<ul><li>6 Rules</li></ul><ul><li>5 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_privileged_identity_Lateral_Movement.md)          |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       |  app-activity<br> ↳ [beyondtrust-pi-app-activity](Parsers/parserContent_beyondtrust-pi-app-activity.md)<br><br> privileged-access<br> ↳ [beyondtrust-pi-privilege-access](Parsers/parserContent_beyondtrust-pi-privilege-access.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>                                              | [<ul><li>7 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_privileged_identity_Malware_Detection.md)         |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  app-activity<br> ↳ [beyondtrust-pi-app-activity](Parsers/parserContent_beyondtrust-pi-app-activity.md)<br><br> privileged-access<br> ↳ [beyondtrust-pi-privilege-access](Parsers/parserContent_beyondtrust-pi-privilege-access.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                                     | [<ul><li>5 Rules</li></ul><ul><li>3 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_privileged_identity_Privileged_Activity.md)       |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    |  app-activity<br> ↳ [beyondtrust-pi-app-activity](Parsers/parserContent_beyondtrust-pi-app-activity.md)<br><br> privileged-access<br> ↳ [beyondtrust-pi-privilege-access](Parsers/parserContent_beyondtrust-pi-privilege-access.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>                                              | [<ul><li>7 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_beyondtrust_beyondtrust_privileged_identity_Ransomware_Detection.md)      |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |