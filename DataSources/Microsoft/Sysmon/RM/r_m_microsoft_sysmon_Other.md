Vendor: Microsoft
=================
### Product: [Sysmon](../ds_microsoft_sysmon.md)
### Use-Case: [Other](../../../../UseCases/uc_other.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  103  |   6    |     0      |      8      |    8    |

| Event Type      | Rules | Models                                                                                                                                                                                                                                         |
| --------------- | ----- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| file-write      |       |  • <b>A-FW-ProcessName-FileName</b>: File creations for process<br> • <b>A-EPA-UP-TEMP</b>: Processes executed from TEMP directories on this asset                                                                                             |
| process-alert   |       |  • <b>A-EPA-UP-TEMP</b>: Processes executed from TEMP directories on this asset                                                                                                                                                                |
| process-created |       |  • <b>A-PC-Process-Hash</b>: Hashes used to create processes on the asset.<br> • <b>A-PC-ParentName-ProcessName</b>: Processes for parent parent processes.<br> • <b>A-EPA-UP-TEMP</b>: Processes executed from TEMP directories on this asset |
| process-network |       |  • <b>A-NET-OdPort-Outbound</b>: Outbound destination ports per organization<br> • <b>A-NET-HdPort-Outbound</b>: Outbound destination ports per asset<br> • <b>A-EPA-UP-TEMP</b>: Processes executed from TEMP directories on this asset       |