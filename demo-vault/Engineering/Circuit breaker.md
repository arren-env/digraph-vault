---
created: 2024-07-12
tags: [eng/reliability]
---

# Circuit breaker

Stop calling a failing dependency for a while so it can recover and you fail fast.
States: closed, open, half-open. Pair with [[Backpressure]] and good [[Observability]].
