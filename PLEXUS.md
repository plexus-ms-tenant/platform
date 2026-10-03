---
plx: v0
profile: platform
---

- The platform host (vm102) is a guest on the damage tenant's hypervisor, and its VM backups are taken there, by the damage tenant's backup server and with its key, in a namespace of their own.
  § 3.1 PLX keeps backups per tenant; both tenants have the same operator and this host holds no state, so it rides along rather than getting a backup path of its own.
