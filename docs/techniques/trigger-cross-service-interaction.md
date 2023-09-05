---
hide:
  - toc
  - footer
---

# Trigger cross-service interaction

!!! info inline end
    ID: MS-T823<br>
    Tactic: [Lateral movement](../tactics/LateralMovement/index.md) <br>
    MITRE technique: 

Attackers may manipulate storage services to trigger a compute service, like Azure Functions, where an attacker already has a foothold on a storage container and can inject a blob that will initiate a chain of a compute process. This may allow an attacker to infiltrate another resource and cause harm.
