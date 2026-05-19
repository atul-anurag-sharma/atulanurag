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

  # Removed "Professional Summary" markdown block completely

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
      text: ""
    demo: true
    design:
      card:
        css_class: bg-red-600
        css_style: ""
        
  - block: contact
    content:
      title: Contact
      subtitle: ""

      autolink: true

      email: aanurag@ramapo.edu
      phone: "862-237-1632"

      address:
        street: "505 Ramapo Valley Road, Office G128H"
        city: "Mahwah"
        region: "NJ"
        postcode: "07430"
        country: "United States"

      coordinates:
        latitude: 41.0819
        longitude: -74.1749

      directions: "Office G128H, Ramapo College of New Jersey"

      office_hours:
        - "Tuesday / Friday 2:50–3:50 PM"

    design:
      columns: "2"        

---