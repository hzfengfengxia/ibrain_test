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
            filename: meshe.png
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
      slide_height: '600px'
      is_fullscreen: false
      loop: true
      interval: 4000

  - block: hero
    content:
      title: |
        i-BRAIN
      image:
        filename: ibrainlogo2.png
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

  - block: features
    content:
      title: Research Areas
      subtitle: Our cutting-edge research focuses on three main areas
      items:
        - name: Brain-Computer Interfaces
          description: Developing next-generation neural interfaces for direct brain-computer communication
          icon: brain
          icon_pack: fas
        - name: Nanoelectronics
          description: Creating ultra-small electronic devices using semiconductor nanowires
          icon: microchip
          icon_pack: fas
        - name: Bioelectronics
          description: Integrating electronics with biological systems for medical applications
          icon: heartbeat
          icon_pack: fas
    design:
      columns: '3'

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
