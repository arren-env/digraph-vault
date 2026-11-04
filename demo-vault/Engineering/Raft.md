---
created: 2024-02-02
tags: [eng/distributed, status/evergreen]
aliases: ["Raft consensus"]
---

# Raft

Consensus algorithm designed to be understandable. Three pieces:

1. [[Leader election]] with randomized timeouts
2. Log replication from the leader
3. Safety: only nodes with up-to-date logs can win an election

![[raft-diagram.png]]

Compare with [[Paxos]]. Used by etcd and Consul.
