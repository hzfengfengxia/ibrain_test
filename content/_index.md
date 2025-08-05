---
title: Research Areas
date: 2022-10-24

type: landing

sections:
  - block: hero
    content:
      title: Our Research Areas
      text: |
        Exploring cutting-edge technologies at the intersection of neuroscience, engineering, and artificial intelligence.
      image:
        filename: welcome.jpg
    design:
      spacing:
        padding: ['40px', '0', '40px', '0']

  - block: features
    content:
      title: Core Research Areas
      subtitle: Three main pillars of our research
      items:
        - name: Brain-Computer Interfaces
          description: |
            Developing next-generation neural interfaces for direct brain-computer communication. 
            Our work focuses on invasive and non-invasive BCI systems, real-time neural signal processing, 
            and clinical applications for paralyzed patients.
          icon: brain
          icon_pack: fas
        - name: Nanoelectronics
          description: |
            Creating ultra-small electronic devices using semiconductor nanowires and advanced fabrication techniques. 
            We design novel nanostructures for high-performance electronics and biomedical applications.
          icon: microchip
          icon_pack: fas
        - name: Bioelectronics
          description: |
            Integrating electronics with biological systems for medical applications and therapeutic interventions. 
            Our research includes implantable devices, biosensors, and neural prosthetics.
          icon: heartbeat
          icon_pack: fas
    design:
      columns: '3'

  - block: markdown
    content:
      title: Research Highlights
      subtitle: 
      text: |
        ## 🧠 Brain-Computer Interface Systems
        
        ### Current Projects:
        - **High-density neural recording arrays** - Developing flexible electrode arrays for chronic neural recording
        - **Real-time BCI decoding** - Machine learning algorithms for motor intention decoding
        - **Clinical BCI trials** - Translating research to help paralyzed patients control devices
        
        ### Key Publications:
        - Nature Neuroscience (2023): "Flexible mesh electronics for chronic neural interfaces"
        - Science Translational Medicine (2022): "Real-time BCI control of robotic arms"
        
        ---
        
        ## ⚡ Nanoelectronics & Device Physics
        
        ### Current Projects:
        - **Semiconductor nanowire synthesis** - Controlled growth of III-V nanowires
        - **Single nanowire devices** - Ultra-sensitive transistors and photodetectors
        - **Quantum devices** - Exploring quantum effects in nanoscale systems
        
        ### Key Publications:
        - Nature Materials (2023): "Controlled synthesis of InAs nanowires"
        - Nano Letters (2022): "Single nanowire quantum devices"
        
        ---
        
        ## 🔬 Bioelectronics & Neural Engineering
        
        ### Current Projects:
        - **Injectable mesh electronics** - Minimally invasive neural interfaces
        - **Biocompatible materials** - Long-term stable neural electrodes
        - **Wireless neural devices** - Battery-free implantable systems
        
        ### Key Publications:
        - Nature Biotechnology (2023): "Injectable mesh electronics for brain monitoring"
        - Advanced Materials (2022): "Biocompatible neural electrodes"
    design:
      columns: '1'

  - block: collection
    content:
      title: Related Publications
      text: ""
      count: 6
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: cta
    content:
      title: Interested in Our Research?
      text: |
        Join our team or collaborate with us on cutting-edge research projects.
      button:
        text: 'Contact Us'
        url: './contact/'
    design:
      columns: '1'
      background:
        gradient_start: '#4bb6ff'
        gradient_end: '#2563eb'
        text_color_light: true
---