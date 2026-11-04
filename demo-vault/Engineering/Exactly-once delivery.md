---
created: 2024-04-03
tags: [eng/distributed]
---

# Exactly-once delivery

Not achievable at the network level. What you actually build is at-least-once delivery plus [[Idempotency keys]] on the consumer.
Kafka transactions are one implementation, see [[Kafka]].
