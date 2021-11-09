Vendor: Proofpoint
==================
Product: Proofpoint DLP
-----------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  43   |   20   |     4      |      4      |    4    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Data Leak](../../../UseCases/uc_data_leak.md) |  dlp-email-alert-in<br> ↳[proofpoint-m1](Ps/pC_proofpointm1.md)<br> ↳[proofpoint-m2](Ps/pC_proofpointm2.md)<br> ↳[proofpoint-m5](Ps/pC_proofpointm5.md)<br> ↳[proofpoint-m15](Ps/pC_proofpointm15.md)<br><br> dlp-email-alert-in-failed<br> ↳[proofpoint-m1](Ps/pC_proofpointm1.md)<br> ↳[proofpoint-m2](Ps/pC_proofpointm2.md)<br> ↳[proofpoint-m5](Ps/pC_proofpointm5.md)<br> ↳[proofpoint-m15](Ps/pC_proofpointm15.md)<br><br> dlp-email-alert-out<br> ↳[proofpoint-m1](Ps/pC_proofpointm1.md)<br> ↳[proofpoint-m2](Ps/pC_proofpointm2.md)<br> ↳[proofpoint-m5](Ps/pC_proofpointm5.md)<br> ↳[proofpoint-m6](Ps/pC_proofpointm6.md)<br><br> dlp-email-alert-out-failed<br> ↳[proofpoint-m1](Ps/pC_proofpointm1.md)<br> ↳[proofpoint-m2](Ps/pC_proofpointm2.md)<br> ↳[proofpoint-m5](Ps/pC_proofpointm5.md)<br> ↳[proofpoint-m6](Ps/pC_proofpointm6.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br> | [<ul><li>39 Rules</li></ul><ul><li>19 Models</li></ul>](RM/r_m_proofpoint_proofpoint_dlp_Data_Leak.md) |
|  [Phishing](../../../UseCases/uc_phishing.md)  |  dlp-email-alert-in<br> ↳[proofpoint-m1](Ps/pC_proofpointm1.md)<br> ↳[proofpoint-m2](Ps/pC_proofpointm2.md)<br> ↳[proofpoint-m5](Ps/pC_proofpointm5.md)<br> ↳[proofpoint-m15](Ps/pC_proofpointm15.md)<br><br> dlp-email-alert-in-failed<br> ↳[proofpoint-m1](Ps/pC_proofpointm1.md)<br> ↳[proofpoint-m2](Ps/pC_proofpointm2.md)<br> ↳[proofpoint-m5](Ps/pC_proofpointm5.md)<br> ↳[proofpoint-m15](Ps/pC_proofpointm15.md)<br><br> dlp-email-alert-out<br> ↳[proofpoint-m1](Ps/pC_proofpointm1.md)<br> ↳[proofpoint-m2](Ps/pC_proofpointm2.md)<br> ↳[proofpoint-m5](Ps/pC_proofpointm5.md)<br> ↳[proofpoint-m6](Ps/pC_proofpointm6.md)<br><br> dlp-email-alert-out-failed<br> ↳[proofpoint-m1](Ps/pC_proofpointm1.md)<br> ↳[proofpoint-m2](Ps/pC_proofpointm2.md)<br> ↳[proofpoint-m5](Ps/pC_proofpointm5.md)<br> ↳[proofpoint-m6](Ps/pC_proofpointm6.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>    | [<ul><li>14 Rules</li></ul><ul><li>7 Models</li></ul>](RM/r_m_proofpoint_proofpoint_dlp_Phishing.md)   |
[Next Page -->>](2_ds_proofpoint_proofpoint_dlp.md)

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                                                                                                                                                                                                                                                    | Impact |
| ------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br>[Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |