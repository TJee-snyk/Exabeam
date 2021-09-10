Vendor: Microsoft
=================
### Product: [Cloud App Security (MCAS)](../ds_microsoft_cloud_app_security_(mcas).md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  60   |   16   |     17     |     12      |   12    |

| Event Type             | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| process-created        | <b>T1021.003 - T1021.003</b><br> ↳ <b>A-DCOMActivation-Known</b>: Remote DCOM activation under DcomLaunch service on this asset.<br> ↳ <b>ParentName-ProcessName-DCOM-F</b>: First time child process creation for DCOM associated process<br> ↳ <b>ParentName-ProcessName-DCOM-A</b>: Abnormal child process creation for DCOM associated process.<br> ↳ <b>DCOMActivation-Known</b>: Remote DCOM activation under DcomLaunch service<br><br><b>T1190 - Exploit Public Fasing Application</b><b>T1210 - Exploitation of Remote Services</b><br> ↳ <b>Terminal-Svc-Proc-Spawn</b>: Process spawned by the terminal service server<br><br><b>T1090 - Proxy</b><br> ↳ <b>A-Netsh-Port-Fwd</b>: Netsh commands were used to configure port forwarding on this asset.<br> ↳ <b>Netsh-Connections-Win-Firewall</b>: Netsh commands were used to allow incoming connections by Port or Application on Windows Firewall.<br> ↳ <b>Netsh-Port-Fwd</b>: Netsh commands were used to configure port forwarding.<br><br><b>T1021 - Remote Services</b><br> ↳ <b>Netsh-RDP-Port-Fwd</b>: Netsh commands used to configure port forwarding for port 3389, used for RDP, were detected.<br><br><b>T1047 - Windows Management Instrumentation</b><b>T1175 - T1175</b><br> ↳ <b>A-Impacket-Lateral-Detection</b>: Activity related to Impacket framework using wmiexec, dcomexe, or smbexec processes via command line have been found on this asset.<br> ↳ <b>Impacket-Lateral-Detection</b>: Activity related to Impacket framework using wmiexec, dcomexe, or smbexec processes via command line have been found.<br><br><b>T1021.002 - Remote Services: SMB/Windows Admin Shares</b><b>T1059 - Command and Scripting Interperter</b><b>T1083 - File and Directory Discovery</b><b>T1135 - Network Share Discovery</b><br> ↳ <b>A-TurlaGroup-LateralMovement</b>: Artifacts from the ATP 'Turla Group' have been observed on this asset<br> ↳ <b>TurlaGroup-LateralMovement</b>: Artifacts from the ATP 'Turla Group' have been observed<br><br><b>T1021.001 - Remote Services: Remote Desktop Protocol</b><br> ↳ <b>A-Suspicious-RDP-TSCON</b>: Suspicious usage of RDP using tscon.exe on this asset<br> ↳ <b>Suspicious-RDP-TSCON</b>: Suspicious usage of RDP using tscon.exe<br><br><b>T1219 - Remote Access Software</b><br> ↳ <b>A-EPA-RAT-TSS</b>: TeamViewer remote desktop access service started on this asset<br> ↳ <b>A-EPA-RAT-SSI</b>: Splashtop remote desktop access service installed on this asset<br> ↳ <b>A-EPA-RAT-TI</b>: TeamViewer remote desktop access agent installed on this asset<br> ↳ <b>A-EPA-RAT-SSS</b>: Splashtop remote desktop access service started on this asset<br> ↳ <b>A-EPA-RAT-SI</b>: Splashtop remote desktop access agent installed on this asset<br> ↳ <b>A-EPA-RAT-GSS</b>: GoToMyPC remote desktop access service started on this asset<br> ↳ <b>A-EPA-RAT-GSI</b>: GoToMyPC remote desktop access service installed on this asset<br> ↳ <b>A-EPA-RAT-TSI</b>: TeamViewer remote desktop access service installed on this asset<br> ↳ <b>A-EPA-RAT-LSS</b>: LogMeIn remote desktop access service started on this asset<br> ↳ <b>A-EPA-RAT-LSI</b>: LogMeIn remote desktop access service installed on this asset<br> ↳ <b>A-EPA-RAT-LI</b>: LogMeIn remote desktop access agent installed on this asset<br> ↳ <b>A-EPA-RAT-GI</b>: GoToMyPC remote desktop access agent installed on this asset<br> ↳ <b>A-TSCON-LocalSystem</b>: Tscon.exe was executed as Local System on this asset<br> ↳ <b>EPA-RAT-GSI</b>: GoToMyPC remote desktop access service installed by this user<br> ↳ <b>EPA-RAT-LSS</b>: LogMeIn remote desktop access service started by this user<br> ↳ <b>EPA-RAT-LI</b>: LogMeIn remote desktop access agent installed by this user<br> ↳ <b>EPA-RAT-SSI</b>: Splashtop remote desktop access service installed by this user<br> ↳ <b>EPA-RAT-SI</b>: Splashtop remote desktop access agent installed by this user<br> ↳ <b>EPA-RAT-TSI</b>: TeamViewer remote desktop access service installed by this user<br> ↳ <b>EPA-RAT-GI</b>: GoToMyPC remote desktop access agent installed by this user<br> ↳ <b>EPA-RAT-TI</b>: TeamViewer remote desktop access agent installed by this user<br> ↳ <b>EPA-RAT-GSS</b>: GoToMyPC remote desktop access service started by this user<br> ↳ <b>EPA-RAT-TSS</b>: TeamViewer remote desktop access service started by this user<br> ↳ <b>EPA-RAT-SSS</b>: Splashtop remote desktop access service started by this user<br> ↳ <b>EPA-RAT-LSI</b>: LogMeIn remote desktop access service installed by this user |  • <b>PC-ParentName-ProcessName</b>: Child processes created by a parent process<br> • <b>A-PC-ParentName-ProcessName</b>: Processes for parent parent processes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| process-network        | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>NET-TI-H-Outbound</b>: Outbound connection to a known malicious host<br> ↳ <b>NET-ZsH-Outbound-A</b>: Abnormal outbound connection for asset for zone<br> ↳ <b>NET-HsH-Outbound-F</b>: First outbound connection for asset<br> ↳ <b>NET-OsZ-Outbound-F</b>: First outbound connection from zone for organization<br> ↳ <b>NET-ZsZ-Outbound-A</b>: Abnormal outbound connection from zone for asset<br> ↳ <b>NET-HsZ-Outbound-F</b>: First outbound connection from zone for asset<br> ↳ <b>NET-HsZ-Outbound-A</b>: Abnormal outbound connection from zone<br> ↳ <b>NET-ZdH-Inbound-A</b>: Abnormal inbound connection to host for the zone.<br> ↳ <b>NET-OdZ-Inbound-F</b>: First inbound connection to zone.<br> ↳ <b>NET-OdZ-Inbound-A</b>: Abnormal inbound connection to zone.<br><br><b>T1571 - Non-Standard Port</b><br> ↳ <b>NET-HdPort-Outbound-F</b>: First outbound connection on port for asset<br> ↳ <b>NET-HdPort-Outbound-A</b>: Abnormal outbound connection to destination port for the asset.<br> ↳ <b>NET-ZdPort-Outbound-F</b>: First outbound connection on port for zone<br> ↳ <b>NET-OdPort-Outbound-A</b>: Abnormal outbound traffic to port for the organization.<br><br><b>T1090.002 - Proxy: External Proxy</b><br> ↳ <b>NET-ZCountry-Inbound-A</b>: Abnormal connection from this country for the zone<br> ↳ <b>NET-OCountry-Inbound-F</b>: First inbound connection from this country for organization<br> ↳ <b>NET-ZCountry-Outbound-A</b>: Abnormal outbound connection country for the zone<br> ↳ <b>NET-OCountry-Outbound-F</b>: First outbound connection to this country from organization                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |  • <b>A-NET-OdZ-Inbound</b>: Network zones with inbound communication in the organization<br> • <b>A-NET-ZdH-Inbound</b>: Hosts receiving inbound communications in the zone<br> • <b>A-NET-HsZ-Outbound</b>: Outbound communicating zones for the asset<br> • <b>A-NET-ZsZ-Outbound</b>: Outbound communicating zones<br> • <b>A-NET-OsZ-Outbound</b>: Outbound communicating zones in the organization<br> • <b>A-NET-HsH-Outbound</b>: Outbound communicating hosts for the asset<br> • <b>A-NET-ZsH-Outbound</b>: Outbound communicating hosts in the zone<br> • <b>A-NET-OdPort-Outbound</b>: Outbound destination ports per organization<br> • <b>A-NET-OCountry-Outbound</b>: Outbound country per organization<br> • <b>A-NET-ZCountry-Outbound</b>: Outbound country per zone<br> • <b>A-NET-OCountry-Inbound</b>: Origination country per organization<br> • <b>A-NET-ZCountry-Inbound</b>: Origination country per zone<br> • <b>A-NET-ZdPort-Outbound</b>: Outbound destination ports per zone<br> • <b>A-NET-HdPort-Outbound</b>: Outbound destination ports per asset |
| process-network-failed | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>NETF-TI-IP-Outbound</b>: Outbound failed connection to a known malicious IP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| security-alert         | <b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>ALERT-DL</b>: DL Correlation rule alert on asset accessed by this user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |