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
        # folders:
        #   - teaching
        folders: [""]  # This tells Hugo to look in the current folder

    design:
      view: article-grid
      columns: 2
---