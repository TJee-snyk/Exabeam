Vendor: Sophos
==============
Product: Sophos UTM
-------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  32   |   10   |     4      |      1      |    1    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                                                                                                                       | MITRE TTP                                                                                                     | Content                                                                                              |
|:--------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  <br> ↳ [sophos-proxy](Parsers/parserContent_sophos-proxy.md)<br> ↳ [sophos-proxy-2](Parsers/parserContent_sophos-proxy-2.md)<br><br> web-activity-denied<br> ↳ [sophos-proxy](Parsers/parserContent_sophos-proxy.md)<br> ↳ [sophos-proxy-1](Parsers/parserContent_sophos-proxy-1.md)<br> | T1071 - Application Layer Protocol<br>T1102 - Web Service<br>T1188 - T1188<br>T1189 - Drive-by Compromise<br> | [<ul><li>32 Rules</li></ul><ul><li>10 Models</li></ul>](Rules_Models/r_m_sophos_sophos_utm_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                           | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                             | Exfiltration | Impact |
| ------------------------------------------------------------------------ | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [Drive-by Compromise](https://attack.mitre.org/techniques/T1189)<br><br> |           |             |                      |                 |                   |           |                  |            | [Web Service](https://attack.mitre.org/techniques/T1102)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br> |              |        |