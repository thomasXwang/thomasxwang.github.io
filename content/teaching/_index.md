---
title: Teaching
summary: My courses
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        files:
          - teaching/teaching.md
    design:
      view: article-list  # Using article-list to display the single file content better
      columns: 1  # Using 1 column for better readability in a single file
---