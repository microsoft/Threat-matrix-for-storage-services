---
hide:
  - toc
  - footer
---

# Code injection

!!! info inline end
    ID: MS-T824<br>
    Tactic: [Lateral movement](../tactics/LateralMovement/index.md) <br>
    MITRE technique: 

Benign code stored on a storage service may be tainted by adding malicious programs, scripts, or exploit code to otherwise valid files. Upon execution of the tainted code by a legitimate user, the malicious portion runs the adversary’s code on a remote system. Attackers may use tainted code to move laterally from the executing host.
Same is applicable for data blobs or files which may be eventually processed on a host by a legitimate application with software vulnerabilities. Attackers may tamper benign data with a payload that exploits a vulnerability on a user's end and execute a malicious code.
