Vendor: Sophos
==============
### Product: [Sophos Endpoint Protection](../ds_sophos_sophos_endpoint_protection.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  13   |   7    |     4      |      9      |    9    |

| Event Type                | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| network-connection-failed | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>NETF-TI-IP-Outbound</b>: Outbound failed connection to a known malicious IP<br> ↳ <b>NET-TI-H-Outbound</b>: Outbound connection to a known malicious host<br> ↳ <b>NETF-OsH-Outbound-F</b>: First failed outbound connection for host in the organization<br> ↳ <b>NETF-HsH-Outbound-F</b>: First failed outbound connection for host<br> ↳ <b>NETF-HsH-Outbound-A</b>: Abnormal outbound connection from host failed<br> ↳ <b>NETF-OsZ-Outbound-F</b>: First failed outbound connection from zone<br><br><b>T1090.002 - Proxy: External Proxy</b><br> ↳ <b>NETF-ZCountry-Outbound-F</b>: First failed outbound connection to this country from zone<br> ↳ <b>NETF-ZsH-Outbound-A</b>: Abnormal outbound connection from host failed in the zone<br><br><b>T1571 - Non-Standard Port</b><br> ↳ <b>NETF-HdPort-Outbound-F</b>: First failed outbound connection on port for asset<br> ↳ <b>NETF-HdPort-Outbound-A</b>: Outbound connection to abnormal port for asset has failed<br> ↳ <b>NETF-OdPort-Outbound-F</b>: First outbound traffic to previously unused port for the organization failed<br> ↳ <b>NETF-OdPort-Outbound-A</b>: Outbound traffic to abnormal port for the organization failed |  • <b>A-NET-OsZ-Outbound</b>: Outbound communicating zones in the organization<br> • <b>A-NET-HsH-Outbound</b>: Outbound communicating hosts for the asset<br> • <b>A-NET-ZsH-Outbound</b>: Outbound communicating hosts in the zone<br> • <b>A-NET-OsH-Outbound</b>: Outbound communicating hosts<br> • <b>A-NET-OdPort-Outbound</b>: Outbound destination ports per organization<br> • <b>A-NETF-ZCountry-Outbound</b>: Failed outbound country per zone<br> • <b>A-NET-HdPort-Outbound</b>: Outbound destination ports per asset |
| security-alert            | <b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>ALERT-DL</b>: DL Correlation rule alert on asset accessed by this user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |