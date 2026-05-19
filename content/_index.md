---
title: Dr. Atul Anurag
date: 2023-08-07
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
      button:
        text: Download CV
        url: files/resume.pdf

  - block: markdown
    content:
      title: Research Interests
      text: |
        Nonlinear Dynamics, Dynamical Systems, Bifurcation Theory

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: 2
      view: card

  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
    design:
      columns: 2
      view: compact

  - block: contact
    id: contact
    content:
      title: Contact
      address:
        street: "Ramapo College of New Jersey, G-128H Office"
        city: Mahwah
        region: NJ
        postcode: "07430"
        country: United States
      coordinates:
        latitude: 41.0814
        longitude: -74.1718
      contact_links:
        - icon: envelope
          icon_pack: fas
          link: "mailto:aanurag@ramapo.edu"

---