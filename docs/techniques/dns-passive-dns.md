---
hide:
  - toc
  - footer
---

# DNS/Passive DNS

!!! info inline end
    ID: MS-T826<br>
    Tactic: [Reconnaissance](../tactics/Reconnaissance/index.md) <br>
    MITRE technique: [T1596.001](http://attack.mitre.org/techniques/T1596/001/)

Attackers may search for DNS data for valid storage account names that can become potential targets. Threat actors can query nameservers using brute-force technique to enumerate existing storage accounts in the wild, or search through centralized repositories of logged DNS query responses (known as passive DNS).
