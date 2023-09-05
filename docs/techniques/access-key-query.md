---
hide:
  - toc
  - footer
---

# Access key query

!!! info inline end
    ID: MS-T818<br>
    Tactic: [Credential access](../tactics/CredentialAccess/index.md) <br>
    MITRE technique: [T1528](https://attack.mitre.org/techniques/T1528)

Attackers may leverage subscription/account-level access to gather storage account keys and use these keys to authenticate at the resource level. This technique exhibits cloud resource pivoting in combination with control management and data planes. Adversaries can query management APIs to fetch primary and secondary storage account keys.
