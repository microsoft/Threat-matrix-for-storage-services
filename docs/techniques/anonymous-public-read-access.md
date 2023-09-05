---
hide:
  - toc
  - footer
---

# Anonymous public read access

!!! info inline end
    ID: MS-T817<br>
    Tactic: [Initial access](../tactics/InitialAccess/index.md) <br>
    MITRE technique: 

Attackers may leverage publicly exposed storage accounts to list containers/blobs and their properties. Azure Storage supports optional anonymous public read access for containers and blobs. By default, anonymous access to your data is never permitted. Unless you explicitly enable anonymous access, all requests to a container and its blobs must be authorized. When you configure a container's public access level setting to permit anonymous access, clients can read data in that container without authorizing the request.
