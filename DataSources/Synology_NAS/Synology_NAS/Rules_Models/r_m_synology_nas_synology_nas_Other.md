Vendor: Synology NAS
====================
### Product: [Synology NAS](../ds_synology_nas_synology_nas.md)
### Use-Case: [Other](../../../../UseCases/uc_other.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  10   |   5    |     3      |      1      |    1    |

| Event Type   | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Models                                                                                                                                                                                                                                                                                                                  |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| share-access | <b>T1068 - Exploitation for Privilege Escalation</b><b>T1087 - Account Discovery</b><br> ↳ <b>SA-Bloodhound-2</b>: ADMIN IPC Share samr folder accessed<br> ↳ <b>SA-Bloodhound-Main</b>: Possible Bloodhound Tool Usage by this user<br><br><b>T1077 - T1077</b><br> ↳ <b>A-SA-ZH-A</b>: Abnormal admin share on asset for zone<br> ↳ <b>A-SA-AsU-F</b>: First access of admin share on asset<br> ↳ <b>SA-OU-F</b>: First admin share access for user in the organization<br> ↳ <b>SA-OU-A</b>: Abnormal admin share access for user in the organization<br> ↳ <b>SA-OH-F</b>: First admin share on this host<br> ↳ <b>SA-OH-A</b>: Abnormal admin share on this host<br> ↳ <b>SA-AsU-F</b>: First access of admin share on this host<br> ↳ <b>SA-AsU-A</b>: Abnormal access of admin share on this host |  • <b>SA-AsU</b>: Users accessing this Admin share<br> • <b>SA-OH</b>: Assets on which admin share is accessed in organization<br> • <b>SA-OU</b>: Users accessing admin share in the organization<br> • <b>A-SA-AsU</b>: Users per Admin share<br> • <b>A-SA-ZH</b>: Assets on which admin shares are accessed in zone |