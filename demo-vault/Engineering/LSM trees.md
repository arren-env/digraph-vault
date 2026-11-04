---
created: 2024-05-06
tags: [eng/data]
---

# LSM trees

Buffer writes in memory, flush sorted runs to disk, merge them in the background.
Great write throughput; reads pay for it with compaction and bloom filters. Contrast with [[B-trees]].
