---
title: ""
date: 2023-08-07
type: landing

sections:

  # =========================
  # HERO / BIOGRAPHY
  # =========================
  - block: about.biography
    id: about
    content:
      title: Dr. Atul Anurag
      username: admin
      text: ""
      button:
        text: Download CV
        url: files/resume.pdf
    design:
      spacing: 0.8rem

  # =========================
  # RESEARCH INTERESTS
  # =========================
  - block: markdown
    id: interests
    content:
      title: Research Interests
      text: |
        Dynamical Systems · Nonlinear Dynamics · Bifurcation Theory
    design:
      columns: 1

  # =========================
  # PUBLICATIONS
  # =========================
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: 2
      view: citation

  # =========================
  # TALKS
  # =========================
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

  # =========================
  # EXPERIENCE
  # =========================
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Visiting Assistant Professor
          company: Ramapo College of New Jersey
          date_start: "2025-08-01"
          location: Mahwah, NJ

        - title: PhD in Applied Mathematics
          company: New Jersey Institute of Technology
          date_start: "2019-08-01"
          date_end: "2025-05-01"
          location: Newark, NJ

    design:
      columns: 2

  # =========================
  # CONTACT + MAP
  # =========================
  - block: contact
    id: contact
    content:
      title: Contact

      address:
        street: "G128H, Ramapo College of New Jersey"
        city: Mahwah
        region: NJ
        postcode: "07430"
        country: United States

      coordinates:
        latitude: "41.0826"
        longitude: "-74.1740"

      contact_links:
        - icon: envelope
          name: Email
          link: mailto:your-email@ramapo.edu

        - icon: brands/github
          name: GitHub
          link: https://github.com/atul-anurag-sharma

        - icon: brands/linkedin
          name: LinkedIn
          link: https://linkedin.com

    design:
      columns: 2
---