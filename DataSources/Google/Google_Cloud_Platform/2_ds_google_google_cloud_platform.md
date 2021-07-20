|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
|   [Cloud Data Protection](../../../UseCases/uc_cloud_data_protection.md)   |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1078.004 - Valid Accounts: Cloud Accounts<br>T1136.003 - Create Account: Create: Cloud Account<br>T1530 - Data from Cloud Storage Object<br> | [<ul><li>31 Rules</li></ul><ul><li>15 Models</li></ul>](RM/r_m_google_google_cloud_platform_Cloud_Data_Protection.md)   |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>19 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_google_google_cloud_platform_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>16 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_google_google_cloud_platform_Data_Access.md)    |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1114.003 - Email Collection: Email Forwarding Rule<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_google_google_cloud_platform_Data_Leak.md)    |
|    [Evasion](../../../UseCases/uc_evasion.md)    |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_google_google_cloud_platform_Evasion.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_google_google_cloud_platform_Malware.md)    |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>7 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_google_google_cloud_platform_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_google_google_cloud_platform_Privilege_Escalation.md)      |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_google_google_cloud_platform_Privileged_Activity.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-activity<br> ↳[googlecloud-app-activity](Ps/pC_googlecloudappactivity.md)<br><br> cloud-admin-activity<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> cloud-admin-activity-failed<br> ↳[googlecloud-iam-activity](Ps/pC_googlecloudiamactivity.md)<br> ↳[googlecloud-cloudresourcemanager-activity](Ps/pC_googlecloudcloudresourcemanageractivity.md)<br><br> storage-access<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br><br> storage-activity-failed<br> ↳[googlecloud-storage-activity](Ps/pC_googlecloudstorageactivity.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_google_google_cloud_platform_Ransomware.md)    |