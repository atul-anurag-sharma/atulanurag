---
title: ""
type: landing
design:
  spacing: 0.5rem

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: CV
        url: files/resume.pdf

  - block: collection
    content:
      filters:
        featured_only: true
        folders:
          - publication
      title: Publications
    design:
      columns: 2
      view: auto
    id: papers

  - block: collection
    content:
      filters:
        folders:
          - events
      title: Recent & Upcoming Talks
    design:
      columns: 2
      view: article-grid
    id: events

  - block: card
    content:
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        css_class: bg-red-600