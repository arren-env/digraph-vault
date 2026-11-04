---
created: 2024-02-03
tags: [eng/distributed]
---

# Leader election

Pick one node to coordinate. Needs fencing tokens so a paused old leader can't corrupt state.
See [[Raft]] and the lease discussion in [[Designing Data-Intensive Applications]].
