---
title: Timeline
created: 2026-07-22
updated: 2026-09-04
tags:
  - 유형/깃헙-개발-블로그-글
unlisted: true
comments: false
---

```base
filters:
  and:
    - "!created.isEmpty()"
views:
  - type: table
    name: "2026"
    filters:
      and:
        - created >= "2026-01-01"
        - created <= "2026-12-31"
    order:
      - created
      - title
    sort:
      - property: created
        direction: DESC
  - type: table
    name: "2027"
    filters:
      and:
        - created >= "2027-01-01"
        - created <= "2027-12-31"
    order:
      - created
      - title
    sort:
      - property: created
        direction: DESC
```
