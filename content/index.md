---
publish: true
title: 딥러닝 노트
created: 2026-11-08T12:47:35.081Z
modified: 2026-11-08T16:02:16.117Z
published: 2026-11-08T16:02:16.117Z
---

```base
views:
  - type: table
    name: 뷰
    filters:
      and:
        - 역할.contains("blog")
    groupBy:
      property: 역할
      direction: ASC
    order:
      - file.name
      - tags
    columnWidth: 270

```
