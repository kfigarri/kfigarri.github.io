---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  ## Featured Articles
  - block: collection
    id: papers
    content:
      title: Featured Articles
      filters:
        folders:
          - publication
          - post
        featured_only: true
    design:
      view: article-grid
      columns: 3
  - block: collection
    content:
      title: Recent Publication
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  ## Recent Projects 
  - block: collection
    id: news
    content:
      title: Recent Projects
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 4
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
