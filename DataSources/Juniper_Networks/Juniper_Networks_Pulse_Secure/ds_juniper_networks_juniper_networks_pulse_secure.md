Vendor: Juniper Networks
========================
Product: Juniper Networks Pulse Secure
--------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  52   |   6    |     6      |      3      |    3    |

|                                  Use-Case                                  | Activity Types                                                                                                                                                                                                                                                                                        | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | MITRE TTP                                                                                                                                                               | Content                                                                                                                                            |
|:--------------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) | <ul><li>Account Creation and Management</li><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Email Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li><li>VPN Activity</li></ul> |  account-deleted<br> ↳ [s-pulsesecure-account-deleted](Parsers/parserContent_s-pulsesecure-account-deleted.md)<br> ↳ [pulsesecure-account-deleted](Parsers/parserContent_pulsesecure-account-deleted.md)<br><br> app-activity<br> ↳ [s-juniper-pulse-activity](Parsers/parserContent_s-juniper-pulse-activity.md)<br> ↳ [cef-juniper-pulse-activity](Parsers/parserContent_cef-juniper-pulse-activity.md)<br><br> vpn-login<br> ↳ [pulsesecure-vpn-login](Parsers/parserContent_pulsesecure-vpn-login.md)<br> ↳ [s-pulsesecure-vpn-login](Parsers/parserContent_s-pulsesecure-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1133 - External Remote Services<br> | [<ul><li>41 Rules</li></ul><ul><li>5 Models</li></ul>](Rules_Models/r_m_juniper_networks_juniper_networks_pulse_secure_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       | <ul><li>Email Activity</li></ul>                                                                                                                                                                                                                                                                      |  account-deleted<br> ↳ [s-pulsesecure-account-deleted](Parsers/parserContent_s-pulsesecure-account-deleted.md)<br> ↳ [pulsesecure-account-deleted](Parsers/parserContent_pulsesecure-account-deleted.md)<br><br> app-activity<br> ↳ [s-juniper-pulse-activity](Parsers/parserContent_s-juniper-pulse-activity.md)<br> ↳ [cef-juniper-pulse-activity](Parsers/parserContent_cef-juniper-pulse-activity.md)<br><br> vpn-login<br> ↳ [pulsesecure-vpn-login](Parsers/parserContent_pulsesecure-vpn-login.md)<br> ↳ [s-pulsesecure-vpn-login](Parsers/parserContent_s-pulsesecure-vpn-login.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1114.003 - Email Collection: Email Forwarding Rule<br>                                        | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_juniper_networks_juniper_networks_pulse_secure_Data_Exfiltration.md)                                  |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          | <ul><li>Application Activity</li></ul>                                                                                                                                                                                                                                                                |  account-deleted<br> ↳ [s-pulsesecure-account-deleted](Parsers/parserContent_s-pulsesecure-account-deleted.md)<br> ↳ [pulsesecure-account-deleted](Parsers/parserContent_pulsesecure-account-deleted.md)<br><br> app-activity<br> ↳ [s-juniper-pulse-activity](Parsers/parserContent_s-juniper-pulse-activity.md)<br> ↳ [cef-juniper-pulse-activity](Parsers/parserContent_cef-juniper-pulse-activity.md)<br><br> vpn-login<br> ↳ [pulsesecure-vpn-login](Parsers/parserContent_pulsesecure-vpn-login.md)<br> ↳ [s-pulsesecure-vpn-login](Parsers/parserContent_s-pulsesecure-vpn-login.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                              | [<ul><li>13 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_juniper_networks_juniper_networks_pulse_secure_Internal_Fraud.md)          |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Network zones and Location Access</li></ul>                                                                                                                                                                                      |  account-deleted<br> ↳ [s-pulsesecure-account-deleted](Parsers/parserContent_s-pulsesecure-account-deleted.md)<br> ↳ [pulsesecure-account-deleted](Parsers/parserContent_pulsesecure-account-deleted.md)<br><br> app-activity<br> ↳ [s-juniper-pulse-activity](Parsers/parserContent_s-juniper-pulse-activity.md)<br> ↳ [cef-juniper-pulse-activity](Parsers/parserContent_cef-juniper-pulse-activity.md)<br><br> vpn-login<br> ↳ [pulsesecure-vpn-login](Parsers/parserContent_pulsesecure-vpn-login.md)<br> ↳ [s-pulsesecure-vpn-login](Parsers/parserContent_s-pulsesecure-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                                                          | [<ul><li>6 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_juniper_networks_juniper_networks_pulse_secure_Lateral_Movement.md)         |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                                                                              |  account-deleted<br> ↳ [s-pulsesecure-account-deleted](Parsers/parserContent_s-pulsesecure-account-deleted.md)<br> ↳ [pulsesecure-account-deleted](Parsers/parserContent_pulsesecure-account-deleted.md)<br><br> app-activity<br> ↳ [s-juniper-pulse-activity](Parsers/parserContent_s-juniper-pulse-activity.md)<br> ↳ [cef-juniper-pulse-activity](Parsers/parserContent_cef-juniper-pulse-activity.md)<br><br> vpn-login<br> ↳ [pulsesecure-vpn-login](Parsers/parserContent_pulsesecure-vpn-login.md)<br> ↳ [s-pulsesecure-vpn-login](Parsers/parserContent_s-pulsesecure-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>                                                                                                        | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_juniper_networks_juniper_networks_pulse_secure_Malware_Detection.md)                                  |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     | <ul><li>Account Creation and Management</li><li>Application Activity</li><li>Email Activity</li><li>Service Account Activity</li></ul>                                                                                                                                                                |  account-deleted<br> ↳ [s-pulsesecure-account-deleted](Parsers/parserContent_s-pulsesecure-account-deleted.md)<br> ↳ [pulsesecure-account-deleted](Parsers/parserContent_pulsesecure-account-deleted.md)<br><br> app-activity<br> ↳ [s-juniper-pulse-activity](Parsers/parserContent_s-juniper-pulse-activity.md)<br> ↳ [cef-juniper-pulse-activity](Parsers/parserContent_cef-juniper-pulse-activity.md)<br><br> vpn-login<br> ↳ [pulsesecure-vpn-login](Parsers/parserContent_pulsesecure-vpn-login.md)<br> ↳ [s-pulsesecure-vpn-login](Parsers/parserContent_s-pulsesecure-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1098 - Account Manipulation<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>                                     | [<ul><li>6 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_juniper_networks_juniper_networks_pulse_secure_Privileged_Activity.md)      |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                                                                              |  account-deleted<br> ↳ [s-pulsesecure-account-deleted](Parsers/parserContent_s-pulsesecure-account-deleted.md)<br> ↳ [pulsesecure-account-deleted](Parsers/parserContent_pulsesecure-account-deleted.md)<br><br> app-activity<br> ↳ [s-juniper-pulse-activity](Parsers/parserContent_s-juniper-pulse-activity.md)<br> ↳ [cef-juniper-pulse-activity](Parsers/parserContent_cef-juniper-pulse-activity.md)<br><br> vpn-login<br> ↳ [pulsesecure-vpn-login](Parsers/parserContent_pulsesecure-vpn-login.md)<br> ↳ [s-pulsesecure-vpn-login](Parsers/parserContent_s-pulsesecure-vpn-login.md)<br> | T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>                                                                                                        | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_juniper_networks_juniper_networks_pulse_secure_Ransomware_Detection.md)                               |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |