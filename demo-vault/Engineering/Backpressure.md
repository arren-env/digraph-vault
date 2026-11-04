---
created: 2024-07-11
tags: [eng/reliability, status/evergreen]
---

# Backpressure

Backpressure protects slow consumers. When a downstream can't keep up, signal upstream to slow down instead of buffering forever.

Options: bounded queues, [[Rate limiting]], load shedding. If you skip it, the failure shows up as memory growth and then a [[Circuit breaker]] tripping somewhere else.
