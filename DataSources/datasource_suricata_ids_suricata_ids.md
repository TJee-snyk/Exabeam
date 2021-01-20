Vendor: Suricata IDS
====================
Product: Suricata IDS
---------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   8   |   2    |     2      |      2      |    2    |

|                              Use-Case                               | Activity Types                                               | Event Types/Parsers                                                                                   | MITRE TTP                  | Content                                             |
|:-------------------------------------------------------------------:| ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------- | -------------------------- | --------------------------------------------------- |
|    [Malware Detection](../UseCases/usecase_malware_detection.md)    | <ul><li>Endpoint Activity</li><li>Process Activity</li></ul> |  network-alert<br> ↳ [suricata-network-alert](../Parsers/parserContent_suricata-network-alert.md)<br> | T1204 - User Execution<br> | <ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul> |
| [Ransomware Detection](../UseCases/usecase_ransomware_detection.md) | <ul><li>Endpoint Activity</li><li>Process Activity</li></ul> |  network-alert<br> ↳ [suricata-network-alert](../Parsers/parserContent_suricata-network-alert.md)<br> | T1204 - User Execution<br> | <ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul> |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution                                                           | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| -------------- | ------------------------------------------------------------------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
|                | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> |             |                      |                 |                   |           |                  |            |                     |              |        |