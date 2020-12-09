Vendor: HashiCorp
=================
Product: HashiCorp Vault
------------------------
|                                 Use-Case                                  | Activity Types                                                                                                                                                                     | Event Types/Parsers                                                                                                                                                                                                 | MITRE TTP                                                      | Content                    |
|:-------------------------------------------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | - Activity Time  and Type<br>- Application Activity<br>- Asset Logon and Access<br>- Critical System Activity<br>- Network zones and Location Access<br>- Service Account Activity |  account-password-reset<br> -- [hashicorp-password-reset](../Parsers/parserContent_hashicorp-password-reset.md)<br><br> app-login<br> -- [hashicorp-app-login](../Parsers/parserContent_hashicorp-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> |  - 22 Rules<br> - 4 Models |
|          [Internal Fraud](../UseCases/usecase_internal_fraud.md)          | - Application Activity                                                                                                                                                             |  account-password-reset<br> -- [hashicorp-password-reset](../Parsers/parserContent_hashicorp-password-reset.md)<br><br> app-login<br> -- [hashicorp-app-login](../Parsers/parserContent_hashicorp-app-login.md)<br> | T1078 - Valid Accounts<br>                                     |  - 4 Rules<br>             |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | - Activity Time  and Type<br>- Application Activity<br>- Network zones and Location Access                                                                                         |  account-password-reset<br> -- [hashicorp-password-reset](../Parsers/parserContent_hashicorp-password-reset.md)<br><br> app-login<br> -- [hashicorp-app-login](../Parsers/parserContent_hashicorp-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> |  - 3 Rules<br> - 1 Models  |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | - Asset Logon and Access                                                                                                                                                           |  account-password-reset<br> -- [hashicorp-password-reset](../Parsers/parserContent_hashicorp-password-reset.md)<br><br> app-login<br> -- [hashicorp-app-login](../Parsers/parserContent_hashicorp-app-login.md)<br> | T1188 - T1188<br>                                              |  - 3 Rules<br>             |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | - Service Account Activity                                                                                                                                                         |  account-password-reset<br> -- [hashicorp-password-reset](../Parsers/parserContent_hashicorp-password-reset.md)<br><br> app-login<br> -- [hashicorp-app-login](../Parsers/parserContent_hashicorp-app-login.md)<br> | T1078 - Valid Accounts<br>                                     |  - 1 Rules<br>             |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | - Asset Logon and Access                                                                                                                                                           |  account-password-reset<br> -- [hashicorp-password-reset](../Parsers/parserContent_hashicorp-password-reset.md)<br><br> app-login<br> -- [hashicorp-app-login](../Parsers/parserContent_hashicorp-app-login.md)<br> | T1188 - T1188<br>                                              |  - 3 Rules<br>             |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilage escalation                                                | Defense evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |