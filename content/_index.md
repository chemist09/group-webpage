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

        We investigate how peptides self-assemble and interact with interfaces to control biological function and dysfunction. We connect mechanisms of peptide aggregation and membrane activity with the rational design of biomolecular materials.

  - block: markdown
    content:
      title:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: features
    content:
      title: Research Areas
      items:
      - name: Interface-Controlled Peptide Self-Assembly
        icon: layer-group
        icon_pack: fas
        description: >
          We study how biological and synthetic interfaces, including nanoparticles, surfaces, and soft matter, direct and modulate peptide self-assembly pathways, with a focus on amyloid fibril formation, corona effects, and interface-driven aggregation relevant to neurodegenerative diseases.
      - name: Sequence-Guided Design of Functional Peptide Fibrils
        icon: diagram-next
        icon_pack: fas
        description: >
          We decode how peptide sequence encodes fibril structure, polymorphism, and function. Using molecular simulations and biophysical experiments, we establish sequence–structure–function relationships that guide the rational design of peptide fibrils and hybrid biomaterials for applications in catalysis, regenerative medicine, and biosensing.
      - name: Membrane Activity of Self-Assembling and Antimicrobial Peptides
        icon: bacon
        icon_pack: fas
        description: >
          We investigate how self-assembling and antimicrobial peptides interact with lipid membranes, exploring how membrane composition, oxidation state, and peptide aggregation govern membrane activity, selectivity, and biological function.

  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: compact
      columns: '1'

  - block: collection
    content:
      title: Latest News
      text: ""
      count: 5
      filters:
        folders:
          - post
      offset: 0
      order: desc
    design:
      view: list
      columns: '1'

  - block: markdown
    content:
      title: Join the Lab
      subtitle:
      text: |
        We welcome motivated students and researchers with backgrounds in chemistry, biochemistry, biophysics, or computational science. Projects combine experimental and computational approaches.

        {{% cta cta_link="./join/" cta_text="Open positions and how to apply →" %}}
    design:
      columns: '1'

  # Background image spacer
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