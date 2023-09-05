---
hide:
  - toc
  - footer
---

# Firewall and virtual networks configuration changes

!!! info inline end
    ID: MS-T813<br>
    Tactic: [Defense Evasion](../tactics/DefenseEvasion/index.md) <br>
            [Persistence](../tactics/Persistence/index.md) <br>
    MITRE technique: [T1562.007](https://attack.mitre.org/techniques/T1562/007/)

 Attackers may disable firewall protection or set additional firewall rules to masquerade their access channel.  Azure Storage offers a set of built-in network access features. Administrators can leverage these capabilities to restrict access to storage resources. Restriction rules can operate at the IP level or VNet IDs. When network rules are configured, only requests originated from authorized subnets will be served. 
