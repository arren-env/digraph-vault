---
created: 2024-09-14
tags: [eng/infra]
---

# Kubernetes notes

Running k3s in the [[Homelab]]. Still need to understand [[Kubernetes operators]] properly.
Liveness probes that hit the database are a bad idea: one slow query restarts every pod.
