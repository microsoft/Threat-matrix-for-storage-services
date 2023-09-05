---
hide:
  - toc
  - footer
---

# Object replication

!!! info inline end
    ID: MS-T840<br>
    Tactic: [Persistence](../tactics/Persistence/index.md) <br>
         [Exfiltration](../tactics/Exfiltration/index.md) <br>
    MITRE technique: [T1537](http://attack.mitre.org/techniques/T1537/)

Attackers may set a replication policy between source and destination containers that asynchronously copies objects from source to destination. This feature can be maliciously misused in both directions. Outbound replication can serve as an exfiltration channel of customer data from the victim's container to an adversary's container. Inbound replication can be used to deliver malware from an adversary's container to a victim's container. After the policy is set, the attacker can operate on their container without accessing the victim container.
