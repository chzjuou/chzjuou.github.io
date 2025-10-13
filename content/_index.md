---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-12-10
type: landing

sections:
  
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
   
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - post
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  - block: collection
    id: featured
    content:
      title: Publications
      text: |
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please feel free to contact me if you have any questions or concerns!
      # Contact (add or remove contact options as necessary)
      email: hchenrsjp@gmail.com
      # phone: +81-08087005028
      address: 
        street: Engineering Science Bldg. F531-33
        city: Machikaneyamacho 1-3, Toyonaka
        region: Osaka
        postcode: '560-8531'
        country: Japan
        country_code: JP
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '34.80433760143029'
        longitude: '135.455413995823'  
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
