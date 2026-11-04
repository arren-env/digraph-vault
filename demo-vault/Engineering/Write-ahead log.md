---
created: 2024-05-01
tags: [eng/data]
aliases: ["WAL"]
---

# Write-ahead log

Write the change to an append-only log before applying it, so you can recover after a crash.
Postgres, SQLite and most databases do this. See [[Postgres MVCC]] and [[LSM trees]].
