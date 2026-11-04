---
created: 2024-06-02
tags: [eng/data, eng/architecture]
---

# Event sourcing

Store the sequence of events, derive current state by replaying them.
Pairs naturally with [[CQRS]] and a log like [[Kafka]]. Watch out for schema evolution of old events.
