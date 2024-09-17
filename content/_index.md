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
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: photo-1554110397-9bac083977c6.jpeg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
   # Add the new 'Fundings' section here
  - block: content
    content:
      title: "Fundings"
      text: |
        ### Fundings

        **Shenzhen Medical Research Fund (SMRF)**  
        *PI, Jan 2024 - Dec 2024*  

        **Project Title**: Research on Real-time Risk Identification Self-Prediction Model and Intelligent Intervention System for Elderly People's Gait Based on Deep Learning Large Model and Deep Imaging Data.  

        **Funding**: ¥50000.  

        **Project Approval No.**: A2301041.
    design:
      background:
        color: "#f9f9f9" 
---
