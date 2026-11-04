---
created: 2024-04-02
tags: [eng/distributed, status/evergreen]
---

# Idempotency keys

Client sends a unique key per logical operation; server stores the result and replays it on retry.
The practical way to get [[Exactly-once delivery]] semantics on top of at-least-once networks.

Used for the payments retry bug at work, see [[2024-04-03]].
