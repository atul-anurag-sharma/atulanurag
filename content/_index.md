---
title: ""
date: 
type: landing

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: files/resume.pdf
    design:
      css_class: auto
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
    
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
#      email: 'aatulanurag@gmail.com'
#      phone: '862-237-1632'
#      appointment_url: ''
      address:
        street: ' 323 Dr Martin Luther King Jr Blvd,
        Cullimore Hall, Suite 105'
        city: 'Newark'
        region: NJ
        postcode: '07102'
        country: United States
        country_code: US
      coordinates:
        latitude: ''
        longitude: ''
#      directions: Enter the Cullimore Hall and walk to Office 105 on Floor 1
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'

  - block: collection
    content:
      filters:
        folders:
          - events
      title: Recent & Upcoming Talks
    design:
      columns: 2
      view: card
    id: events

  - block: collection
    content:
      count: 5
      filters:
        author: "admin"
        category: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
        tag: ""
      offset: 0
      order: desc
      page_type: post
      subtitle: ""
      text: ""
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
        css_class: bg-primary-700
        css_style: ""
---