|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
|     [Lateral Movement](../../../UseCases/uc_lateral_movement.md)     |  authentication-failed<br> ↳[mastersam-pam-remote-logon](Ps/pC_mastersampamremotelogon.md)<br><br> authentication-successful<br> ↳[mastersam-pam-auth-failed-3](Ps/pC_mastersampamauthfailed3.md)<br> ↳[mastersam-pam-auth-failed-2](Ps/pC_mastersampamauthfailed2.md)<br><br> failed-physical-access<br> ↳[mastersam-pam-auth-successful-1](Ps/pC_mastersampamauthsuccessful1.md)<br> ↳[mastersam-pam-auth-successful-3](Ps/pC_mastersampamauthsuccessful3.md)<br><br> remote-logon<br> ↳[mastersam-pam-password-change](Ps/pC_mastersampampasswordchange.md)<br> | T1018 - Remote System Discovery<br>T1021 - Remote Services<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1550 - Use Alternate Authentication Material<br>T1550.002 - Use Alternate Authentication Material: Pass the Hash<br>T1550.003 - Use Alternate Authentication Material: Pass the Ticket<br>T1558 - Steal or Forge Kerberos Tickets<br>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br> | [<ul><li>31 Rules</li></ul><ul><li>14 Models</li></ul>](RM/r_m_mastersam_mastersam_pam_Lateral_Movement.md)   |
|    [Malware](../../../UseCases/uc_malware.md)    |  authentication-failed<br> ↳[mastersam-pam-remote-logon](Ps/pC_mastersampamremotelogon.md)<br><br> authentication-successful<br> ↳[mastersam-pam-auth-failed-3](Ps/pC_mastersampamauthfailed3.md)<br> ↳[mastersam-pam-auth-failed-2](Ps/pC_mastersampamauthfailed2.md)<br><br> failed-physical-access<br> ↳[mastersam-pam-auth-successful-1](Ps/pC_mastersampamauthsuccessful1.md)<br> ↳[mastersam-pam-auth-successful-3](Ps/pC_mastersampamauthsuccessful3.md)<br><br> remote-logon<br> ↳[mastersam-pam-password-change](Ps/pC_mastersampampasswordchange.md)<br> | T1078 - Valid Accounts<br>T1550.003 - Use Alternate Authentication Material: Pass the Ticket<br>T1558 - Steal or Forge Kerberos Tickets<br>TA0002 - TA0002<br>    | [<ul><li>6 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_mastersam_mastersam_pam_Malware.md)    |
|    [Physical Security](../../../UseCases/uc_physical_security.md)    |  authentication-failed<br> ↳[mastersam-pam-remote-logon](Ps/pC_mastersampamremotelogon.md)<br><br> authentication-successful<br> ↳[mastersam-pam-auth-failed-3](Ps/pC_mastersampamauthfailed3.md)<br> ↳[mastersam-pam-auth-failed-2](Ps/pC_mastersampamauthfailed2.md)<br><br> failed-physical-access<br> ↳[mastersam-pam-auth-successful-1](Ps/pC_mastersampamauthsuccessful1.md)<br> ↳[mastersam-pam-auth-successful-3](Ps/pC_mastersampamauthsuccessful3.md)<br><br> remote-logon<br> ↳[mastersam-pam-password-change](Ps/pC_mastersampampasswordchange.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>5 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_mastersam_mastersam_pam_Physical_Security.md)    |
|      [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)      |  authentication-failed<br> ↳[mastersam-pam-remote-logon](Ps/pC_mastersampamremotelogon.md)<br><br> authentication-successful<br> ↳[mastersam-pam-auth-failed-3](Ps/pC_mastersampamauthfailed3.md)<br> ↳[mastersam-pam-auth-failed-2](Ps/pC_mastersampamauthfailed2.md)<br><br> failed-physical-access<br> ↳[mastersam-pam-auth-successful-1](Ps/pC_mastersampamauthsuccessful1.md)<br> ↳[mastersam-pam-auth-successful-3](Ps/pC_mastersampamauthsuccessful3.md)<br><br> remote-logon<br> ↳[mastersam-pam-password-change](Ps/pC_mastersampampasswordchange.md)<br> | T1078 - Valid Accounts<br>T1078.002 - T1078.002<br>    | [<ul><li>10 Rules</li></ul><ul><li>7 Models</li></ul>](RM/r_m_mastersam_mastersam_pam_Privilege_Abuse.md)     |
| [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md) |  authentication-failed<br> ↳[mastersam-pam-remote-logon](Ps/pC_mastersampamremotelogon.md)<br><br> authentication-successful<br> ↳[mastersam-pam-auth-failed-3](Ps/pC_mastersampamauthfailed3.md)<br> ↳[mastersam-pam-auth-failed-2](Ps/pC_mastersampamauthfailed2.md)<br><br> failed-physical-access<br> ↳[mastersam-pam-auth-successful-1](Ps/pC_mastersampamauthsuccessful1.md)<br> ↳[mastersam-pam-auth-successful-3](Ps/pC_mastersampamauthsuccessful3.md)<br><br> remote-logon<br> ↳[mastersam-pam-password-change](Ps/pC_mastersampampasswordchange.md)<br> | T1078 - Valid Accounts<br>T1555.005 - T1555.005<br>    | [<ul><li>2 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_mastersam_mastersam_pam_Privilege_Escalation.md) |
|  [Privileged Activity](../../../UseCases/uc_privileged_activity.md)  |  authentication-failed<br> ↳[mastersam-pam-remote-logon](Ps/pC_mastersampamremotelogon.md)<br><br> authentication-successful<br> ↳[mastersam-pam-auth-failed-3](Ps/pC_mastersampamauthfailed3.md)<br> ↳[mastersam-pam-auth-failed-2](Ps/pC_mastersampamauthfailed2.md)<br><br> failed-physical-access<br> ↳[mastersam-pam-auth-successful-1](Ps/pC_mastersampamauthsuccessful1.md)<br> ↳[mastersam-pam-auth-successful-3](Ps/pC_mastersampamauthsuccessful3.md)<br><br> remote-logon<br> ↳[mastersam-pam-password-change](Ps/pC_mastersampampasswordchange.md)<br> | T1021 - Remote Services<br>T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>T1078.002 - T1078.002<br>    | [<ul><li>18 Rules</li></ul><ul><li>8 Models</li></ul>](RM/r_m_mastersam_mastersam_pam_Privileged_Activity.md) |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  authentication-failed<br> ↳[mastersam-pam-remote-logon](Ps/pC_mastersampamremotelogon.md)<br><br> authentication-successful<br> ↳[mastersam-pam-auth-failed-3](Ps/pC_mastersampamauthfailed3.md)<br> ↳[mastersam-pam-auth-failed-2](Ps/pC_mastersampamauthfailed2.md)<br><br> failed-physical-access<br> ↳[mastersam-pam-auth-successful-1](Ps/pC_mastersampamauthsuccessful1.md)<br> ↳[mastersam-pam-auth-successful-3](Ps/pC_mastersampamauthsuccessful3.md)<br><br> remote-logon<br> ↳[mastersam-pam-password-change](Ps/pC_mastersampampasswordchange.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_mastersam_mastersam_pam_Ransomware.md)    |