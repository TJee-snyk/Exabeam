Vendor: Proofpoint
==================
Product: Proofpoint Enterprise Protection
-----------------------------------------
|                                 Use-Case                                  | Activity Types                                                      | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | MITRE TTP                                                                    | Content                    |
|:-------------------------------------------------------------------------:| ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | -------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | - Critical System Activity                                          |  dlp-alert<br> -- [json-s-proofpoint-email-alert-2](../Parsers/parserContent_json-s-proofpoint-email-alert-2.md)<br> -- [cef-proofpoint-dlp-alert-1](../Parsers/parserContent_cef-proofpoint-dlp-alert-1.md)<br> -- [s-proofpoint-email-alert-2](../Parsers/parserContent_s-proofpoint-email-alert-2.md)<br><br> dlp-email-alert-in<br> -- [s-proofpoint-email-alert](../Parsers/parserContent_s-proofpoint-email-alert.md)<br><br> dlp-email-alert-in-failed<br> -- [s-proofpoint-email-alert](../Parsers/parserContent_s-proofpoint-email-alert.md)<br> | T1078 - Valid Accounts<br>                                                   |  - 1 Rules<br>             |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | - Data Loss Prevention                                              |  dlp-alert<br> -- [json-s-proofpoint-email-alert-2](../Parsers/parserContent_json-s-proofpoint-email-alert-2.md)<br> -- [cef-proofpoint-dlp-alert-1](../Parsers/parserContent_cef-proofpoint-dlp-alert-1.md)<br> -- [s-proofpoint-email-alert-2](../Parsers/parserContent_s-proofpoint-email-alert-2.md)<br><br> dlp-email-alert-in<br> -- [s-proofpoint-email-alert](../Parsers/parserContent_s-proofpoint-email-alert.md)<br><br> dlp-email-alert-in-failed<br> -- [s-proofpoint-email-alert](../Parsers/parserContent_s-proofpoint-email-alert.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1204 - User Execution<br> |  - 14 Rules<br> - 3 Models |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | - Data Loss Prevention<br>- Endpoint Activity<br>- Process Activity |  dlp-alert<br> -- [json-s-proofpoint-email-alert-2](../Parsers/parserContent_json-s-proofpoint-email-alert-2.md)<br> -- [cef-proofpoint-dlp-alert-1](../Parsers/parserContent_cef-proofpoint-dlp-alert-1.md)<br> -- [s-proofpoint-email-alert-2](../Parsers/parserContent_s-proofpoint-email-alert-2.md)<br><br> dlp-email-alert-in<br> -- [s-proofpoint-email-alert](../Parsers/parserContent_s-proofpoint-email-alert.md)<br><br> dlp-email-alert-in-failed<br> -- [s-proofpoint-email-alert](../Parsers/parserContent_s-proofpoint-email-alert.md)<br> | T1204 - User Execution<br>                                                   |  - 5 Rules<br> - 1 Models  |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | - Data Loss Prevention<br>- Endpoint Activity<br>- Process Activity |  dlp-alert<br> -- [json-s-proofpoint-email-alert-2](../Parsers/parserContent_json-s-proofpoint-email-alert-2.md)<br> -- [cef-proofpoint-dlp-alert-1](../Parsers/parserContent_cef-proofpoint-dlp-alert-1.md)<br> -- [s-proofpoint-email-alert-2](../Parsers/parserContent_s-proofpoint-email-alert-2.md)<br><br> dlp-email-alert-in<br> -- [s-proofpoint-email-alert](../Parsers/parserContent_s-proofpoint-email-alert.md)<br><br> dlp-email-alert-in-failed<br> -- [s-proofpoint-email-alert](../Parsers/parserContent_s-proofpoint-email-alert.md)<br> | T1204 - User Execution<br>                                                   |  - 5 Rules<br> - 1 Models  |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilage escalation                                                | Defense evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |