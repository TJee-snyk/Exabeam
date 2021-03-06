Vendor: Proofpoint TAP
======================
Product: Proofpoint TAP
-----------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   4   |   0    |     2      |      2      |    2    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                                                   | MITRE TTP                                                                    | Content                                                                              |
|:--------------------------------------:| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| [Other](../../../UseCases/uc_other.md) |  dlp-email-alert-in<br> ↳ [s-proofpoint-email-in](Parsers/parserContent_s-proofpoint-email-in.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-proofpoint-email-in](Parsers/parserContent_s-proofpoint-email-in.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br> | [<ul><li>4 Rules</li></ul>](Rules_Models/r_m_proofpoint_tap_proofpoint_tap_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |