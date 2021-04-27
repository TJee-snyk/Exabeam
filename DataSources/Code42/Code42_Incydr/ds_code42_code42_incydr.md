Vendor: Code42
==============
Product: Code42 Incydr
----------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  48   |   23   |     7      |      9      |    9    |

|                                  Use-Case                                  | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | MITRE TTP                                                                                                                                                                                                                                                                                                            | Content                                                                                                                 |
|:--------------------------------------------------------------------------:| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  dlp-email-alert-out<br> ↳ [code42-email-out-operations](Parsers/parserContent_code42-email-out-operations.md)<br><br> file-delete<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-download<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-read<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-upload<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-write<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> print-activity<br> ↳ [code42-print-operations](Parsers/parserContent_code42-print-operations.md)<br><br> usb-activity<br> ↳ [code42-usb-removed](Parsers/parserContent_code42-usb-removed.md)<br><br> usb-insert<br> ↳ [code42-usb-insert](Parsers/parserContent_code42-usb-insert.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>                                                                                                                                                                                                                                                   | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_code42_code42_incydr_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  dlp-email-alert-out<br> ↳ [code42-email-out-operations](Parsers/parserContent_code42-email-out-operations.md)<br><br> file-delete<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-download<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-read<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-upload<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-write<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> print-activity<br> ↳ [code42-print-operations](Parsers/parserContent_code42-print-operations.md)<br><br> usb-activity<br> ↳ [code42-usb-removed](Parsers/parserContent_code42-usb-removed.md)<br><br> usb-insert<br> ↳ [code42-usb-insert](Parsers/parserContent_code42-usb-insert.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1083 - File and Directory Discovery<br> | [<ul><li>41 Rules</li></ul><ul><li>21 Models</li></ul>](Rules_Models/r_m_code42_code42_incydr_Data_Exfiltration.md)     |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  dlp-email-alert-out<br> ↳ [code42-email-out-operations](Parsers/parserContent_code42-email-out-operations.md)<br><br> file-delete<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-download<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-read<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-upload<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-write<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> print-activity<br> ↳ [code42-print-operations](Parsers/parserContent_code42-print-operations.md)<br><br> usb-activity<br> ↳ [code42-usb-removed](Parsers/parserContent_code42-usb-removed.md)<br><br> usb-insert<br> ↳ [code42-usb-insert](Parsers/parserContent_code42-usb-insert.md)<br> | T1052 - Exfiltration Over Physical Medium<br>                                                                                                                                                                                                                                                                        | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_code42_code42_incydr_Lateral_Movement.md)                                  |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       |  dlp-email-alert-out<br> ↳ [code42-email-out-operations](Parsers/parserContent_code42-email-out-operations.md)<br><br> file-delete<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-download<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-read<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-upload<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-write<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> print-activity<br> ↳ [code42-print-operations](Parsers/parserContent_code42-print-operations.md)<br><br> usb-activity<br> ↳ [code42-usb-removed](Parsers/parserContent_code42-usb-removed.md)<br><br> usb-insert<br> ↳ [code42-usb-insert](Parsers/parserContent_code42-usb-insert.md)<br> | T1204 - User Execution<br>                                                                                                                                                                                                                                                                                           | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_code42_code42_incydr_Malware_Detection.md)       |
|                [Phishing](../../../UseCases/uc_phishing.md)                |  dlp-email-alert-out<br> ↳ [code42-email-out-operations](Parsers/parserContent_code42-email-out-operations.md)<br><br> file-delete<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-download<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-read<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-upload<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-write<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> print-activity<br> ↳ [code42-print-operations](Parsers/parserContent_code42-print-operations.md)<br><br> usb-activity<br> ↳ [code42-usb-removed](Parsers/parserContent_code42-usb-removed.md)<br><br> usb-insert<br> ↳ [code42-usb-insert](Parsers/parserContent_code42-usb-insert.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>                                                                                                                                                   | [<ul><li>7 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_code42_code42_incydr_Phishing.md)                |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    |  dlp-email-alert-out<br> ↳ [code42-email-out-operations](Parsers/parserContent_code42-email-out-operations.md)<br><br> file-delete<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-download<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-read<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> file-upload<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br><br> file-write<br> ↳ [code42-file-operations-4](Parsers/parserContent_code42-file-operations-4.md)<br> ↳ [code42-file-operations-2](Parsers/parserContent_code42-file-operations-2.md)<br> ↳ [code42-file-operations-3](Parsers/parserContent_code42-file-operations-3.md)<br> ↳ [code42-file-operations](Parsers/parserContent_code42-file-operations.md)<br><br> print-activity<br> ↳ [code42-print-operations](Parsers/parserContent_code42-print-operations.md)<br><br> usb-activity<br> ↳ [code42-usb-removed](Parsers/parserContent_code42-usb-removed.md)<br><br> usb-insert<br> ↳ [code42-usb-insert](Parsers/parserContent_code42-usb-insert.md)<br> | T1204 - User Execution<br>                                                                                                                                                                                                                                                                                           | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_code42_code42_incydr_Ransomware_Detection.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery                                                                         | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------------------------------------------------------------------------------- | ---------------- | ---------- | ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br>[Exfiltration Over Physical Medium: Exfiltration over USB](https://attack.mitre.org/techniques/T1052/001)<br><br>[Exfiltration Over Physical Medium](https://attack.mitre.org/techniques/T1052)<br><br>[Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |