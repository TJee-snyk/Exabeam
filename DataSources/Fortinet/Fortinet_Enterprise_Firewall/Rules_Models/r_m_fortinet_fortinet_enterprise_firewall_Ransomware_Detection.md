Vendor: Fortinet
================
### Product: [Fortinet Enterprise Firewall](../ds_fortinet_fortinet_enterprise_firewall.md)
### Use-Case: [Ransomware Detection](../../../../UseCases/uc_ransomware_detection.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  11   |   1    |     4      |      6      |    6    |

| Event Type                    | Rules                                                                                                                                                                                                                                                                                                                                                                                             | Models                                                                                    |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| app-activity                  | <b>T1078 - Valid Accounts</b><br> ↳ <b>Auth-Blacklist-Shost</b>: User authentication or login from a known blacklisted IP<br> ↳ <b>Auth-Ransomware-Shost</b>: User authentication or login from a known ransomware IP<br><br><b>T1090.003 - Proxy: Multi-hop Proxy</b><br> ↳ <b>Auth-Tor-Shost</b>: User authentication or login from a known TOR IP                                              |                                                                                           |
| app-activity-failed           | <b>T1078 - Valid Accounts</b><br> ↳ <b>Auth-Ransomware-Shost-Failed</b>: User authentication or login failure from a known ransomware IP<br><br><b>T1090.003 - Proxy: Multi-hop Proxy</b><br> ↳ <b>Auth-Tor-Shost-Failed</b>: User authentication or login failure from a known TOR IP<br> ↳ <b>Auth-Blacklist-Shost-Failed</b>: User authentication or login failure from a known blacklisted IP |                                                                                           |
| netflow-connection            | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>NET-TI-H-Outbound</b>: Outbound connection to a known malicious host<br> ↳ <b>NET-OdZ-Inbound-F</b>: First inbound connection to zone.<br> ↳ <b>NET-OdZ-Inbound-A</b>: Abnormal inbound connection to zone.                                                                                                                                    |  • <b>A-NET-OdZ-Inbound</b>: Network zones with inbound communication in the organization |
| network-connection-failed     | <b>T1496 - Resource Hijacking</b><br> ↳ <b>A-NET-Coin-IP</b>: Connection to IP associated with cryptocurrency mining<br><br><b>T1071 - Application Layer Protocol</b><br> ↳ <b>NETF-TI-IP-Outbound</b>: Outbound failed connection to a known malicious IP<br> ↳ <b>NET-TI-H-Outbound</b>: Outbound connection to a known malicious host                                                          |                                                                                           |
| network-connection-successful | <b>T1496 - Resource Hijacking</b><br> ↳ <b>A-NET-Coin-IP</b>: Connection to IP associated with cryptocurrency mining<br><br><b>T1071 - Application Layer Protocol</b><br> ↳ <b>NET-TI-H-Outbound</b>: Outbound connection to a known malicious host<br> ↳ <b>NET-OdZ-Inbound-F</b>: First inbound connection to zone.<br> ↳ <b>NET-OdZ-Inbound-A</b>: Abnormal inbound connection to zone.        |  • <b>A-NET-OdZ-Inbound</b>: Network zones with inbound communication in the organization |