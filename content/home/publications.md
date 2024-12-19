---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

headless: true # This file represents a page section.
weight: 40 # Order that this section appears on the page.

title: Publications
subtitle: 

sections:
  - block: collection
    id: publications
    content:
      title: Published/Accepted
      filters:
        folders:
          -submitted_paper
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
  - block: collection
    id: publications
    content:
      title: Submitted
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
  design:
    view: 3 # Choose a view for the listings:
    columns: '2'
---