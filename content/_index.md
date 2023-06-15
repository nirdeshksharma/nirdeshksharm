---
date: "2022-10-24"
sections:

- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 
      icon: satellite
      icon_pack: fa
      name: Remote Sensing
    - description: 
      icon: python
      icon_pack: fab
      name: Python
    - description: 
      icon:  microchip
      icon_pack: fas
      name: machine learning
    - description: 
      icon: gear
      icon_pack: fa
      name: Google Earth Engine
    - description: 
      icon: image
      icon_pack: fa
      name: Data Visualization
    - description: 
      icon: water
      icon_pack: fa
      name: Water Resource Engineering

    title: Skills
    

- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Blog
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Latest
      tag: Latest 
    - name: Old 
      tag: Old 
    default_button_index: 0
    filters:
      folders:
      - project
    title: News
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects

- block: collection
  id: featured
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Journal Publications
  design:
    columns: "2"
    view: card
  id: featured
  
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Conference Publications
  design:
    columns: "2"
    view: citation
    
- block: contact
  content:
    address:
      city: IIT-Delhi
      country: India
      country_code: IN
      postcode: "110016"
      region: Hauz Khas
      street: Hydrosense Labs
    appointment_url:
    autolink: False
    contact_links:
    directions: 
    email: nirdesh@civil.iitd.ac.in
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
