---
hide:
  - toc
  - footer
---

# SFTP account

!!! info inline end
    ID: MS-T809<br>
    Tactic: [Persistence](../tactics/Persistence/index.md) <br>
    MITRE technique:

Attackers may create an SFTP account to maintain access to a target storage account. The SFTP account is local on the storage instance and is not subject to Azure RBAC permissions. The account is also unaffected in case of storage account access keys rotation.
