---
hide:
  - toc
  - footer
---

# Create SAS token

!!! info inline end
    ID: MS-T806<br>
    Tactic: [Persistence](../tactics/Persistence/index.md) <br>
    MITRE technique:

Attackers may create a high-privileged SAS token with long expiry to preserve valid credentials for a long period. The tokens are not monitored by storage accounts thus they cannot be revoked (except Service SAS) and it's not easy to determine whether there are valid tokens in the wild until they are used.
