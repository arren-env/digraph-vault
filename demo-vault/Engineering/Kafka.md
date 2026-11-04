---
created: 2024-04-10
tags: [eng/data]
---

# Kafka

Distributed append-only log. Partitions give ordering per key; consumer groups give parallelism.
Under the hood it's a [[Write-ahead log]] you can read from.

Related: [[Event sourcing]], [[Backpressure]], [[Exactly-once delivery]].
