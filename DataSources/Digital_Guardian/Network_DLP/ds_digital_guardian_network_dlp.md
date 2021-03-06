Vendor: Digital Guardian
========================
Product: Network DLP
--------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  29   |   12   |     2      |      1      |    1    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                                                                        | MITRE TTP                                                                    | Content                                                                                                         |
|:--------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  dlp-email-alert-out<br> ↳ [leef-digitalguardian-dlp-email-alert-out](Parsers/parserContent_leef-digitalguardian-dlp-email-alert-out.md)<br> ↳ [cef-digitalguardian-send-mail](Parsers/parserContent_cef-digitalguardian-send-mail.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br> | [<ul><li>29 Rules</li></ul><ul><li>12 Models</li></ul>](Rules_Models/r_m_digital_guardian_network_dlp_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |