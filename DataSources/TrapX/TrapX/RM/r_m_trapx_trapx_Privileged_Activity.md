Vendor: TrapX
=============
### Product: [TrapX](../ds_trapx_trapx.md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   7   |   3    |     4      |      1      |    1    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| remote-access | <b>T1021 - Remote Services</b><br> ↳ <b>RA-UH-CS-NC</b>: Remote access  to a critical system for user with no information<br> ↳ <b>RA-F-F-CS</b>: First remote access to critical system for user<br> ↳ <b>RA-F-A-CS</b>: Abnormal remote access to critical system for user<br> ↳ <b>RA-HT-EXEC-new</b>: New user remote access to executive asset<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>RA-UH-CS-NC</b>: Remote access  to a critical system for user with no information<br> ↳ <b>RA-F-F-CS</b>: First remote access to critical system for user<br> ↳ <b>RA-F-A-CS</b>: Abnormal remote access to critical system for user<br> ↳ <b>DC20b</b>: High-privilege domain account used during session<br> ↳ <b>RA-HT-EXEC-new</b>: New user remote access to executive asset<br><br><b>T1078.002 - T1078.002</b><br> ↳ <b>DC18</b>: First use of domain account by user<br><br><b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>ALERT-EXEC</b>: Security violation by Executive |  • <b>AL-HT-EXEC</b>: Executive Assets<br> • <b>DC18</b>: Secondary accounts<br> • <b>RA-UH</b>: Assets accessed by this user remotely |