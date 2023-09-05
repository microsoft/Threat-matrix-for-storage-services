---
hide:
  - toc
  - footer
---

# Trusted access based on a managed identity

!!! info inline end
    ID: MS-T829<br>
    Tactic: [Persistence](../tactics/Persistence/index.md) <br>
    MITRE technique:

Attackers may configure the storage account firewall to allow access by specific resource instances based on their system-assigned managed identity, regardless of their source address. The resource type can be chosen from a predefined list provided by Azure Storage, and the resource instance must be in the same tenant as the storage account. The RBAC permissions of the resource instance determine the types of operations that a resource instance can perform on storage account data.
