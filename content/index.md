---
publish: true
title: 딥러닝 노트
created: 2026-11-08T12:47:35.081Z
modified: 2026-11-08T15:10:04.060Z
---

```base
views:
  - type: table
    name: 뷰
    filters:
      and:
        - file.inFolder("07. Blog/Deep_Learning")
    groupBy:
      property: 역할
      direction: ASC
    order:
      - file.name
      - tags
    columnWidth: 270

```
