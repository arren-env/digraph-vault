---
created: 2024-06-03
tags: [eng/architecture]
---

# CQRS

Separate the write model from the read model. Worth it when reads and writes have very different shapes.
Often paired with [[Event sourcing]], but doesn't require it.
