---
publish: true
title: 딥러닝 노트
created: 2026-11-08T12:47:35.081Z
modified: 2026-11-08T15:18:33.739Z
published: 2026-11-08T15:18:33.739Z
---

```base
views:
  - type: table
    name: 뷰
    filters:
      and:
        - 역할 == ["blog"]
    groupBy:
      property: 역할
      direction: ASC
    order:
      - file.name
      - tags
    columnWidth: 270

```
