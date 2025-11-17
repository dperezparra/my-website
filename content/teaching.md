---
title: 'Teaching Materials'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: collection
    content:
      title: "Recent Posts"
      subtitle: "Latest updates from our blog"
      text: "Stay up to date with our latest news and insights."
      # Filter content to show posts or publications
      filters:
        folders:
          - post
        featured_only: false
      count: 3
    design:
      view: card
      columns: 3
---
