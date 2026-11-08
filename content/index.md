---
publish: true
title: 딥러닝 노트
created: 2026-11-08T12:47:35.081Z
modified: 2026-11-08T16:13:46.489Z
published: 2026-11-08T16:13:46.489Z
---

hi

```base
views:
  - type: table
    name: 뷰
    filters:
      and:
        - publish == true
        - file.tags.contains("Deep_Learning")
    order:
      - file.name
      - tags

```
