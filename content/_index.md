---
# Leave the homepage title empty to use the site title
title: Brain Fluid Translational Imaging Laboratory
date: 2023-05-24
type: landing

sections:
  - block: hero
    content:
      title: |
        BraFTI
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **BraFTI Research Lab** focuses on developing imaging methods to characterize brain fluid compartments, tissue microstructure, and neurofluid dynamics in health and disease. By perturbing brain fluid compartments, BraFTI aims to develop novel therapeutic and diagnostic approaches.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
