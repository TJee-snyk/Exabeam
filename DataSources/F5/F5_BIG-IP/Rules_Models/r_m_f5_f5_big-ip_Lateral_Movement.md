Vendor: F5
==========
### Product: [F5 BIG-IP](../ds_f5_f5_big-ip.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  41   |   7    |     13     |      5      |    5    |

| Event Type                    | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Models                                                                                                                                                                                                                                                                             |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| authentication-failed         | <b>T1133 - External Remote Services</b><br> ↳ <b>FA-UC-F</b>: Failed activity from a new country                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |  • <b>UA-UC</b>: Countries for user                                                                                                                                                                                                                                                |
| failed-logon                  | <b>T1550.003 - Use Alternate Authentication Material: Pass the Ticket</b><b>T1550.004 - Use Alternate Authentication Material: Web Session Cookie</b><br> ↳ <b>KL-TfG</b>: Rare Kerberos ticket failure code<br><br><b>T1110 - Brute Force</b><br> ↳ <b>FL-MULTI-DEST-M</b>: Failed logins to multiple destinations from host (M)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                                                    |
| failed-vpn-login              | <b>T1133 - External Remote Services</b><br> ↳ <b>FA-UC-F</b>: Failed activity from a new country                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |  • <b>UA-UC</b>: Countries for user                                                                                                                                                                                                                                                |
| network-connection-successful | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>NET-ZsH-Outbound-A</b>: Abnormal outbound connection for asset for zone<br> ↳ <b>NET-HsH-Outbound-F</b>: First outbound connection for asset<br> ↳ <b>NET-OsZ-Outbound-F</b>: First outbound connection from zone for organization<br> ↳ <b>NET-ZsZ-Outbound-A</b>: Abnormal outbound connection from zone for asset<br> ↳ <b>NET-HsZ-Outbound-F</b>: First outbound connection from zone for asset<br> ↳ <b>NET-HsZ-Outbound-A</b>: Abnormal outbound connection from zone<br> ↳ <b>NET-ZdH-Inbound-A</b>: Abnormal inbound connection to host for the zone.<br> ↳ <b>A-NET-Ransomware-IP</b>: Asset attempted to connect to an IP address which is associated to Ransomware<br><br><b>T1571 - Non-Standard Port</b><br> ↳ <b>NET-HdPort-Outbound-F</b>: First outbound connection on port for asset<br> ↳ <b>NET-HdPort-Outbound-A</b>: Abnormal outbound connection to destination port for the asset.<br> ↳ <b>NET-ZdPort-Outbound-F</b>: First outbound connection on port for zone<br> ↳ <b>NET-OdPort-Outbound-A</b>: Abnormal outbound traffic to port for the organization.<br><br><b>T1090.002 - Proxy: External Proxy</b><br> ↳ <b>NET-ZCountry-Inbound-A</b>: Abnormal connection from this country for the zone<br> ↳ <b>NET-OCountry-Inbound-F</b>: First inbound connection from this country for organization<br> ↳ <b>NET-ZCountry-Outbound-A</b>: Abnormal outbound connection country for the zone<br> ↳ <b>NET-OCountry-Outbound-F</b>: First outbound connection to this country from organization                                                                                                                                                                                                                                                                                     |                                                                                                                                                                                                                                                                                    |
| remote-logon                  | <b>T1078 - Valid Accounts</b><br> ↳ <b>A-AL-DhU-A</b>: Abnormal user per asset<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session<br> ↳ <b>AL-HT-EXEC-new</b>: New user logon to executive asset<br> ↳ <b>DC18-new</b>: Account switch by new user<br><br><b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>RL-UH-sZ-F</b>: First remote logon to asset from new or abnormal source network zone<br> ↳ <b>RL-UH-sZ-A</b>: Abnormal remote logon to asset from new or abnormal source network zone<br> ↳ <b>RLA-UsZ-F</b>: First source network zone for user<br> ↳ <b>RLA-UsZ-A</b>: Abnormal source network zone for user<br> ↳ <b>RLA-UsH-dZ-F</b>: First remote access to zone from new asset<br> ↳ <b>RLA-UsH-dZ-A</b>: Abnormal remote access to zone from new asset<br> ↳ <b>RLA-dZsZ-F</b>: First inter-zone communication from destination to source<br> ↳ <b>RLA-sZdZ-F</b>: First inter-zone communication from source to destination<br> ↳ <b>RLA-sZdZ-A</b>: Abnormal inter-zone communication<br> ↳ <b>RL-HU-F-new</b>: Remote logon to private asset for new user<br><br><b>T1550 - Use Alternate Authentication Material</b><br> ↳ <b>RLA-UAPackage-F</b>: First time usage of Windows authentication package<br> ↳ <b>RLA-UAPackage-A</b>: Abnormal usage of Windows authentication package<br><br><b>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting</b><br> ↳ <b>KL-USn-A</b>: Abnormal service to obtain TGTs for user<br><br><b>T1078.003 - Valid Accounts: Local Accounts</b><br> ↳ <b>AL-HLocU-F</b>: First local user logon to this asset<br><br><b>T1018 - Remote System Discovery</b><br> ↳ <b>A-RLRA-AA-A</b>: Abnormal asset-to-asset remote communication<br> ↳ <b>A-RLRA-ZZ-F</b>: First zone-to-zone communication<br> ↳ <b>A-RLRA-ZZ-A</b>: Abnormal zone-to-zone communication |  • <b>RL-HU</b>: Remote logon users<br> • <b>AL-HT-EXEC</b>: Executive Assets<br> • <b>RL-UH</b>: Remote logons<br> • <b>NKL-HU</b>: Users logging into this host remotely<br> • <b>A-RLRA-ZZ</b>: Zone to zone communication<br> • <b>A-RLRA-AA</b>: Asset to asset communication |
| vpn-login                     | <b>T1078 - Valid Accounts</b><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |  • <b>UA-UC</b>: Countries for user                                                                                                                                                                                                                                                |