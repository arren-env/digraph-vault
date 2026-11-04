---
created: 2024-05-20
tags: [eng/data]
---

# Postgres MVCC

Every row version carries xmin/xmax transaction IDs; readers see a snapshot and never block writers.
The cost is dead tuples, which is why VACUUM matters. Relies on the [[Write-ahead log]] for durability.
