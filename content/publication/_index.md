---
title: Publications & Patents
type: landing

sections:
  - block: markdown
    content:
      title: Publications
      subtitle: Our latest research publications
      text: ""
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '10px', '0']

  - block: collection
    content:
      title: ""
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
        publication_type: ''
        tag: 'publication'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: Patents
      subtitle: Our intellectual property portfolio
      text: ""
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '10px', '0']

  - block: collection
    content:
      title: ""
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
        publication_type: ''
        tag: 'patent'
    design:
      view: citation
      columns: '1'
---