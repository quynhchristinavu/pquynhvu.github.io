---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

publications:
  - title: Published/Accepted
    filters:
      folders:
        - submitted_paper
      tag: ''
      category: ''
      publication_type: ''
      author: ''
      exclude_featured: false
      exclude_future: false
      exclude_past: false
    count: 2 # Choose how many pages you would like to display (0 = all pages)
    offset: 0 # Choose how many pages you would like to offset by
    order: desc # Page order: descending (desc) or ascending (asc) date.
  - title: Submitted
    filters:
      folders:
        - publication
      tag: ''
      category: ''
      publication_type: ''
      author: ''
      exclude_featured: false
      exclude_future: false
      exclude_past: false
    count: 2 # Choose how many pages you would like to display (0 = all pages)
    offset: 0 # Choose how many pages you would like to offset by
    order: desc # Page order: descending (desc) or ascending (asc) date.

widget_id: publications
title: Education
headless: true # This file represents a page section.
weight: 40
design:
  view: 3 # Choose a view for the listings:
  columns: '2'
---

{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}
