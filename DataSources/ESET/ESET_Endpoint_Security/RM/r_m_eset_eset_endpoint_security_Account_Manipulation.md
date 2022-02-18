Vendor: ESET
============
### Product: [ESET Endpoint Security](../ds_eset_eset_endpoint_security.md)
### Use-Case: [Account Manipulation](../../../../UseCases/uc_account_manipulation.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   4   |   1    |     1      |      7      |    7    |

| Event Type       | Rules    | Models    |
| ---- | ---- | ---- |
| failed-ds-access | <b>T1484 - Group Policy Modification</b><br> ↳ <b>FDS-OU-F</b>: First directory service event for user and it failed in the organization<br> ↳ <b>FDS-OG-F</b>: First directory service event for user and it failed in the peer group<br> ↳ <b>FDS-OU</b>: Failed directory service event for user in the organization<br> ↳ <b>FDS-OG</b>: Failed directory service event for user in the peer group |  • <b>DS-OG</b>: Users with directory service activity in the peer group |