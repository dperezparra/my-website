---
title: "Research"
slug: "research"
type: landing

sections:
  - block: collection
    content:
      title: "Working Papers"
      # This pulls from your publication section:
      filters:
        folders:
          - publication
      count: 20
    design:
      view: article-grid
      fill_image: true
      columns: 2
      show_date: false
      show_read_time: true
      show_read_more: true
  - block: collection
    content:
      title: Ongoing Work
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
