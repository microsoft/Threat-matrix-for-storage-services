---
hide:
  - toc
  - footer
---

# Trusted Azure services

!!! info inline end
    ID: MS-T830<br>
    Tactic: [Persistence](../tactics/Persistence/index.md) <br>
    MITRE technique:

Attackers may configure the storage account firewall to allow access by trusted Azure services. Azure Storage provides a predefined list of trusted services. Any resource from that list that belongs to the same subscription as the storage account is allowed by the firewall even if there is no firewall rule that explicitly permits the source address of the resource.
