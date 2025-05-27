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
        text: CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: dark
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
          

          
 # - block: markdown
 #   content:
 #     title: '📚 My Research'
 #     subtitle: ''
 #     text: |-
 #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

 #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
 #       Please reach out to collaborate 😃
 #    design:
 #     columns: '1'
      
   
      
  #- block: collection
  #  id: papers
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2
      
      
  - block: collection
    id: publications
    content:
      title: 📚 Publications and Preprints
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      
      
  - block: markdown
    id: talks
    content:
      title: "📢 Selected Talks"
      text: |
        * September 2024 – **[SwissMAP General Meeting 2024](/uploads/prez_SwissMAP2024.pdf)**, Les Diablerets  
        * May 2023 – **[Banff International Research Station Workshop](/uploads/prez_banff.pdf)**, Granada  
        * May 2022 – **[Kinetic Theory seminar](/uploads/prez_kinetic.pdf)**, Zürich  
        * November 2020 – **[Young researchers seminar Ceremade - Université Paris Dauphine](/uploads/prez_dauphine.pdf)**, Paris  
        * October 2019 – **[NumKin 2019](/uploads/prez_numkin.pdf)**, Munich  
        * July 2019 – **[Vlasovia 2019](/uploads/poster_Vlasovia.pdf)** (Poster), Strasbourg  

      
  - block: markdown
    id: teaching
    content:
      title: "📘 Teaching Activities"
      text: |
        * **An Introduction to Partial Differential Equations** (B.Sc. Seminar) – _ETH Zürich_ – 2022  
        * **An Introduction to Mean-Field Limits for Vlasov Equations** (M.Sc. seminar) – _ETH Zürich_ – 2022  
        * **[Applied analysis](/uploads/poly_3M133.pdf)** (3rd year B.Sc.) – _Sorbonne Université_ – 2019  
        * **[Programming in Python](https://python.guillod.org/python001.html)** (3rd year B.Sc.) – _Sorbonne Université_ – 2019  
        * **[Numerical methods for ODEs](/uploads/poly_3M236.pdf)** (3rd year B.Sc.) – _Sorbonne Université_ – 2019 and 2020  
        * **[ODEs: theoretical analysis and numerical approximation](/uploads/poly_2M310.pdf)** (2nd year B.Sc.) – _Sorbonne Université_ – 2019  
        * **Power series, Fourier analysis, Leibniz’s rule and application to ODEs** (2nd year B.Sc.) – _Sorbonne Université_ – 2019  
        * **[Numerical approximation of functions](/uploads/poly_3M234.pdf)** (3rd year B.Sc.) – _Sorbonne Université_ – 2018  
        * **Tutoring classes in mathematics** (1st/2nd year B.Sc.) – _Université Paris Diderot_ – 2016  

      
  - block: markdown
    id: contact
    content:
      title: "📨 Contact"
      text: |
        Feel free to contact me at [alxdr.rege@gmail.com](mailto:alxdr.rege@gmail.com)

      
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    view: article-grid
  #    columns: 1
      
      
  #- block: collection
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
  #    # Page type to display. E.g. post, talk, publication...
  #    page_type: post
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #    filters:
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: date-title-summary
      # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]
        
        
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
