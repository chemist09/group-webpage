---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Biomolecular Systems and Design Lab
      image:
        filename: welcome.png
      text: |
        <br>
        
        We investigate how peptides self-assemble and interact with interfaces to control biological function and dysfunction. Using biophysical experiments and molecular simulations, we uncover mechanisms of peptide aggregation and membrane activity that link disease-related processes with the rational design of biomolecular materials.
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: markdown
    content:
      title: Join the Lab
      subtitle:
      text: |
        The Biomolecular Systems and Design Lab welcomes motivated students with backgrounds in chemistry, biochemistry, biophysics, or related disciplines. Projects typically combine experimental and computational approaches, but applicants are not expected to have prior experience in all methods. Information on open positions can be found via the *Contact* page. Prospective students are also welcome to get in touch to discuss potential opportunities.

        {{% cta cta_link="./contact/" cta_text="Contact →" %}}
    design:
      columns: '1'

  - block: features
    content:
      title: Research Areas
      items:
      - name: Mechanisms of Peptide Self-Assembly
        description: >
          We study how peptides self-assemble into ordered structures, including amyloid fibrils.
          Our work focuses on how sequence, environment, and interfaces regulate aggregation pathways
          relevant to age-related and neurodegenerative diseases.
      - name: Biomolecular Interactions at Interfaces
        description: >
          Interfaces such as membranes and nanoparticles strongly modulate biomolecular behavior.
          We investigate peptide-interface interactions and their role in membrane activity,
          transport, and biological function or dysfunction.
      - name: Design of Functional Bionanomaterials
        description: >
          Using mechanistic insights, we engineer functional biomolecular assemblies.
          Our work aims at the rational design of peptide-based and hybrid materials
          with controlled structure and biological activity.

  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        tag: research
    design:
      view: compact
      columns: '1'

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
      view: list
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: artwork.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
