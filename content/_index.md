---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Mechatronics, Automation, and Control Systems Laboratory 
        {style="color: white"}
      image:
        filename: 
      text: |
        <br>
        
        The MACS Lab investigates theories and practice of dynamic systems and controls, to seek better understanding and engineering of the systematic interplay between data, system, and control in machines and automation processes that positively impact our lives.
        {style="color: white"}
    design:
      columns: '1'
      background:
        video:
          filename: IROS24_2687_VI_fi.mp4
          filters:
            brightness: 0.5
          parallax: false
          position: center
          size: cover
          #text_color_light: ture
      spacing:
        padding: ['20px', '40px', '20px', '40px']
      css_class: fullscreen
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 4
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
      view: compact
      columns: '2'
      background:
        image: 
          filename: MACS_Logo_transparentBg.png
          filters:
            brightness: 0.5
          parallax: false
          position: center
          size: cover
          text_color_light: true

  - block: collection
    content:
      title: Research
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: research
      sort_by: weight
      sort_ascending: false
    design:
      view: showcase
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

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
        <div align="center"> <img src="./Figures/MACS_Logo_transparentBg.png" style="zoom:30%"  alt=""/> </div>
          
    design:
      columns: '1'
---
