Vendor: Sailpoint
=================
### Product: [SecurityIQ](../ds_sailpoint_securityiq.md)
### Use-Case: [Other](../../../../UseCases/uc_other.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  21   |   13   |     6      |     12      |   12    |

| Event Type             | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| account-creation       | <b>T1098 - Account Manipulation</b><br> ↳ <b>AM-DhU-system-F</b>: First account management by system account on asset<br> ↳ <b>AM-UH-F</b>: First account management activity from asset for user<br> ↳ <b>AM-GA-new</b>: First account management activity for group of a new user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>NEW-USER-F</b>: User with no event history                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  • <b>AE-GA</b>: All activity for peer groups<br> • <b>AM-UH</b>: Account management activity on host for user<br> • <b>AE-UA</b>: All activity for users<br> • <b>A-AM-DhU-system</b>: System accounts performing account management activities                                                                                                                                                                                                                                                                                                                                                                                                                              |
| account-deleted        | <b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user<br><br><b>T1098 - Account Manipulation</b><br> ↳ <b>A-ACCT-CR-DEL</b>: Account created and deleted on asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  • <b>AE-UA</b>: All activity for users                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| account-lockout        | <b>T1110 - Brute Force</b><br> ↳ <b>SEQ-UH-01</b>: Account lockout on an asset that belongs to this user<br> ↳ <b>SEQ-UH-02</b>: Account lockout on an asset that does not belong to this user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| account-password-reset | <b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |  • <b>AE-UA</b>: All activity for users                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| file-delete            | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-FG-F</b>: First access to folder for group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group<br> • <b>FA-FG</b>: Folder access by groups                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| file-download          | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| file-permission-change | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-FG-F</b>: First access to folder for group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group<br> • <b>FA-FG</b>: Folder access by groups                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| file-read              | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-FG-F</b>: First access to folder for group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group<br> • <b>FA-FG</b>: Folder access by groups                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| file-upload            | <b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| file-write             | <b>T1204 - User Execution</b><br> ↳ <b>EPA-TEMP-DIRECTORY-F</b>: First execution of this process from a temporary directory on this asset<br> ↳ <b>EPA-TEMP-DIRECTORY-A</b>: Abnormal execution of this process from a temporary directory<br> ↳ <b>FA-TEMP-DIRECTORY-F</b>: First time process has been executed from a temporary directory by this user during file activity<br><br><b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-FG-F</b>: First access to folder for group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account                                                                                                                                                                                                                                                                                                            |  • <b>FA-UP-TEMP</b>: Process executable TEMP directories for this user during file activity<br> • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group<br> • <b>FA-FG</b>: Folder access by groups<br> • <b>A-EPA-UP-TEMP</b>: Processes executed from TEMP directories on this asset                                                                                                                                                                                                                                                                                                                   |
| member-added           | <b>T1098 - Account Manipulation</b><br> ↳ <b>AM-DhU-system-F</b>: First account management by system account on asset<br> ↳ <b>AM-UH-F</b>: First account management activity from asset for user<br> ↳ <b>AM-OU-SS-A</b>: Abnormal addition and removal of member from a group in a single session in the organization<br> ↳ <b>AM-OG-SS-F</b>: First addition and removal of member from a group by user in a single session for peer group<br> ↳ <b>AM-OG-SS-A</b>: Abnormal addition and removal of member from a group in a single session in the peer group<br> ↳ <b>AM-OG-F</b>: First member addition to this group for the organization<br> ↳ <b>AM-GA-new</b>: First account management activity for group of a new user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>NEW-USER-F</b>: User with no event history<br><br><b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>MA-PRIV-F-local</b>: First addition to privileged group by local user<br> ↳ <b>MA-PRIV-A</b>: Abnormal addition to privileged group by user |  • <b>AE-GA</b>: All activity for peer groups<br> • <b>AM-AG</b>: Account management, groups which users are being added to<br> • <b>AM-OG-SS</b>: Models the peer groups who perform addition and removal of members from group in same session<br> • <b>AM-OU-SS</b>: Models the users who perform addition and removal of members from group in same session in the organization<br> • <b>AM-UH</b>: Account management activity on host for user<br> • <b>AM-OU-PG</b>: Account group management of high privileges in the organization<br> • <b>AE-UA</b>: All activity for users<br> • <b>A-AM-DhU-system</b>: System accounts performing account management activities |
| member-removed         | <b>T1098 - Account Manipulation</b><br> ↳ <b>AM-UH-F</b>: First account management activity from asset for user<br> ↳ <b>AM-OU-SS-A</b>: Abnormal addition and removal of member from a group in a single session in the organization<br> ↳ <b>AM-OG-SS-F</b>: First addition and removal of member from a group by user in a single session for peer group<br> ↳ <b>AM-OG-SS-A</b>: Abnormal addition and removal of member from a group in a single session in the peer group<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |  • <b>AM-OG-SS</b>: Models the peer groups who perform addition and removal of members from group in same session<br> • <b>AM-OU-SS</b>: Models the users who perform addition and removal of members from group in same session in the organization<br> • <b>AM-UH</b>: Account management activity on host for user<br> • <b>AE-UA</b>: All activity for users                                                                                                                                                                                                                                                                                                              |