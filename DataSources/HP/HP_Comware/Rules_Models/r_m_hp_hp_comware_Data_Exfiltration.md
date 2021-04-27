Vendor: HP
==========
### Product: [HP Comware](../ds_hp_hp_comware.md)
### Use-Case: [Data Exfiltration](../../../../UseCases/uc_data_exfiltration.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   5   |   0    |     3      |      1      |    1    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Models |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ |
| process-created | <b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>A-Tap-Installer</b>: TAP software was installed on this asset.<br> ↳ <b>DNS-Exfiltration-Tools-Exec</b>: Well-known DNS Exfiltration tools were executed.<br> ↳ <b>Tap-Installer</b>: TAP software was installed.<br><br><b>T1020 - Automated Exfiltration</b><br> ↳ <b>Exfil-Tunnel-Tools-Exec</b>: Tools known for data exfiltration and tunneling were executed.<br><br><b>T1175 - T1175</b><br> ↳ <b>MMC-Spawn-Win-Shell</b>: MMC (Microsoft Management Console) started a Windows command line executable. |        |