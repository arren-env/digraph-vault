---
created: 2024-07-15
tags: [eng/reliability]
---

# Rate limiting

Token bucket for bursts, sliding window for fairness. Return 429 with a Retry-After header.
Implemented one for the [[Recipe Box]] API.
