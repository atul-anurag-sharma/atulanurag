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
        text: CV
        url: files/resume.pdf
    design:
      css_class: ""
      background:
        color: auto
        image:
          filename: 
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

#    content:
#      count: 5
#      filters:
#        author: "admin"
#        category: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#        tag: ""
#      offset: 0
#      order: desc
#      page_type: post
#      subtitle: ""
#      text: ""
#      title: Blog
#    design:
#      columns: 2
#      view: article-grid
#    id: post

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
