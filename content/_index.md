---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Cutting-Edge Brain-Computer Interface Research
        content: Exploring the intersection of neuroscience and artificial intelligence to develop next-generation brain-computer interface technologies
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#666'
        link:
          icon: brain
          icon_pack: fas
          text: Explore Research
          url: ./publication/
      - title: State-of-the-Art Laboratory
        content: World-class laboratory equipped with advanced facilities to support groundbreaking research initiatives
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#555'
        link:
          icon: microscope
          icon_pack: fas
          text: Take a Tour
          url: ./tour/
      - title: Excellence in Team
        content: Bringing together top talents dedicated to advancing neural engineering and biomedical engineering
        align: right
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: users
          icon_pack: fas
          text: Meet the Team
          url: ./people/
    design:
      slide_height: '400px'
      is_fullscreen: false
      loop: true
      interval: 4000

  - block: hero
    content:
      title: |
        i-BRAIN
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        i-BRAIN will create solutions for the near-term but also enable future advances and treatments that today may be considered the realm of science fiction.
  
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

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
