Vendor: F5
==========
Product: Big-IP Access Policy Manager (APM)
-------------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  12   |   4    |     3      |      2      |    2    |

|                                  Use-Case                                  | Activity Types                                                                      | Event Types/Parsers                                                                                                                                                                                                  | MITRE TTP                                                      | Content                                                                                                                                  |
|:--------------------------------------------------------------------------:| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Network zones and Location Access</li></ul> |  authentication-failed<br> ↳ [json-f5-auth-attempt](Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> ↳ [json-f5-auth-attempt](Parsers/parserContent_json-f5-auth-attempt.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | [<ul><li>9 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_f5_big-ip_access_policy_manager_(apm)_Compromised_Credentials.md) |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        | <ul><li>Network zones and Location Access</li></ul>                                 |  authentication-failed<br> ↳ [json-f5-auth-attempt](Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> ↳ [json-f5-auth-attempt](Parsers/parserContent_json-f5-auth-attempt.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_f5_big-ip_access_policy_manager_(apm)_Lateral_Movement.md)        |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       | <ul><li>Asset Logon and Access</li></ul>                                            |  authentication-failed<br> ↳ [json-f5-auth-attempt](Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> ↳ [json-f5-auth-attempt](Parsers/parserContent_json-f5-auth-attempt.md)<br> | T1188 - T1188<br>                                              | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_f5_big-ip_access_policy_manager_(apm)_Malware_Detection.md)                                 |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li></ul>                                            |  authentication-failed<br> ↳ [json-f5-auth-attempt](Parsers/parserContent_json-f5-auth-attempt.md)<br><br> authentication-successful<br> ↳ [json-f5-auth-attempt](Parsers/parserContent_json-f5-auth-attempt.md)<br> | T1188 - T1188<br>                                              | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_f5_big-ip_access_policy_manager_(apm)_Ransomware_Detection.md)                              |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |