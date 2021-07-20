Vendor: F5
==========
### Product: [F5 BIG-IP](../ds_f5_f5_big-ip.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  11   |   4    |     5      |      5      |    5    |

| Event Type                    | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Models                                                                                                  |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| failed-logon                  | <b>T1212 - Exploitation for Credential Access</b><br> ↳ <b>A-Kerberos-Manipulation-Failure</b>: Possible Kerberos failure code triggered by manipulation of Kerberos messages on the asset.<br> ↳ <b>Kerberos-Manipulation-Failure</b>: Rare Kerberos failure code triggered by possible manipulation of Kerberos messages.<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>SEQ-UH-04</b>: Failed logon by a service account<br> ↳ <b>SEQ-UH-05</b>: Failed interactive logon by a service account |  • <b>AE-UA</b>: All activity for users                                                                 |
| failed-vpn-login              | <b>T1133 - External Remote Services</b><br> ↳ <b>SEQ-UH-15</b>: Failed VPN login                                                                                                                                                                                                                                                                                                                                                                                                                 |                                                                                                         |
| network-connection-successful | <b>T1046 - Network Service Scanning</b><br> ↳ <b>NETFLOW-OsH-SweepScan-A</b>: Abnormal for asset to access 20 assets in 10 seconds                                                                                                                                                                                                                                                                                                                                                               |  • <b>A-NETFLOW-OsH-Scanners</b>: Assets that access multiple assets within seconds in the organization |
| remote-logon                  | <b>T1078 - Valid Accounts</b><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br><br><b>T1021 - Remote Services</b><br> ↳ <b>A-RLA-AA-F</b>: First asset-to-asset communication<br> ↳ <b>A-RLA-AA-A</b>: Abnormal asset-to-asset communication                                                                                                                              |  • <b>A-RLA-AA</b>: Asset to asset communication (DISABLED)                                             |
| vpn-login                     | <b>T1078 - Valid Accounts</b><b>T1133 - External Remote Services</b><br> ↳ <b>VPN-GsH-F</b>: First VPN connection from device for peer group<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries                                                                                                                                                                                                                       |  • <b>VPN-GsH</b>: VPN endpoints in this peer group                                                     |