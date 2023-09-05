---
hide:
  - toc
  - footer
---

# Private endpoint

!!! info inline end
    ID: MS-T812<br>
    Tactic: [Defense Evasion](../tactics/DefenseEvasion/index.md) <br>
            [Persistence](../tactics/Persistence/index.md) <br>
    MITRE technique: 

Attackers may set private endpoints for a storage account to establish a separate communication channel from a target virtual network. The new endpoint is assigned with a private IP address within the virtual network's address range. All the requests sent to the private endpoint bypass the storage account firewall by design.
