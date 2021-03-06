Vendor: RSA
===========
Product: RSA DLP
----------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  42   |   19   |     3      |      2      |    2    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                | MITRE TTP                                                                                              | Content                                                                                        |
|:--------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  dlp-alert<br> ↳ [rsa-dlp-alert](Parsers/parserContent_rsa-dlp-alert.md)<br><br> dlp-email-alert-out<br> ↳ [rsa-dlp-email-alert](Parsers/parserContent_rsa-dlp-email-alert.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1204 - User Execution<br> | [<ul><li>42 Rules</li></ul><ul><li>19 Models</li></ul>](Rules_Models/r_m_rsa_rsa_dlp_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |