---
hide:
  - toc
  - footer
---

# Unsecured communication channel

!!! info inline end
    ID: MS-T819<br>
    Tactic: [Credential access](../tactics/CredentialAccess/index.md) <br>
    MITRE technique: [T1040](https://attack.mitre.org/techniques/T1040/)

Attackers may sniff network traffic and capture credentials sent over an insecure protocol. When Storage account is configured to support unencrypted protocol such as HTTP, credentials are passed over the wire unprotected and are susceptible to leakage. The attacker can use the compromised credentials to gain initial access to the storage account. 
