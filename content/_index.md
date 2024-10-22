---
title: ""
date: 
type: landing
design:
  spacing: 0.5rem
sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: files/resume.pdf
    design:
      css_class: ""
      background:
        color: auto
        image:
          filename: ""
          filters:
            brightness: auto
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      subtitle: ""
      text: ""
      title: ""
    design:
      columns: "1"

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

  - block: markdown
    content:
      text: "<div style='height: 4rem; background-color: #f0f0f0; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin: 2rem 0;'></div>"
    design:
      columns: "1"

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

  - block: collection
    content:
      count: 5
      filters:
        author: "admin"
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      order: desc
      page_type: post
      title: Blog
    design:
      columns: 2
      view: article-grid
    id: post

  - block: card
    content:
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
      text: ""
    demo: true
    design:
      card:
        css_class: bg-red-600
        css_style: ""
---
