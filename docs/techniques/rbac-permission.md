---
hide:
  - toc
  - footer
---

# Role-based access control permission

!!! info inline end
    ID: MS-T808<br>
    Tactic: [Defense Evasion](../tactics/DefenseEvasion/index.md) <br>
            [Persistence](../tactics/Persistence/index.md) <br>
    MITRE technique: T1098.001

Storage services offer built-in RBAC roles that encompass sets of permissions used to access different data types. Definition of custom roles is also supported. Upon assignment of an RBAC role to an identity object (like Azure AD security principal) the storage provider grants access to that security principal. Attackers may leverage the RBAC mechanism to ensure persistent access to their owned identity objects.
