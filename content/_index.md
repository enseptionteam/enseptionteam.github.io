---
# Leave the homepage title empty to use the site title
title: 'EnSeption'
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |-
        At EnSeption, we conduct advanced research on AI models designed to analyze multimedia data such as images, video, and audio. Our work focuses not only on developing high-performance AI models, but also on addressing the practical challenges that arise during their deployment. These include insufficient training data, model bias, and performance degradation in real-world environments. To overcome these issues, we explore novel training methodologies as well as techniques for model optimization and lightweight deployment.
        
        We also investigate sensory substitution technologies, which aim to convey information from impaired or weakened sensory channels through alternative modalities. Alongside this, our research extends to wearable systems capable of supplementing or replacing human sensory functions, as well as technologies that enhance human perceptual capabilities more broadly.
        
        Below are examples of our recent publications and technical overviews:
        
        - [Human Visual Ability Enhancement Technology Trends and Development Prospects](https://dx.doi.org/10.22648/ETRI.2024.J.390407), Electronics and Telecommunications Trends, 39(4), 2024.
        - [감각대체를 통한 포용적 기술 개발 (Inclusive Technology Development through Sensory Substitution)](https://kist.re.kr/fcsc/publication/research-review.do?mode=view&articleNo=13089&article.offset=0&articleLimit=10), Convergence Research Review, 10(4), 2024.
  
        We welcome passionate researchers to join our laboratory through the following programs:

        - UST–ETRI School Graduate Programs: M.S., Ph.D., and integrated M.S.–Ph.D. programs in Artificial Intelligence
        - ETRI Post-Master’s / Post-Doctoral Fellowship Programs: For graduates holding M.S. or Ph.D. degrees
        - ETRI Research Internship: For third- and fourth-year undergraduate students, offering a two-month immersive research experience during the summer or winter break
      

      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # # Apply a gradient background
      # css_class: hbx-bg-gradient
      background:
        image:
          filename: background.jpg
          size: cover
          position: center
          parallax: true
          text_color_light: true

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      count: 10
      archive:
        enable: false
    design:
      view: citation

  # - block: markdown
  #   id: team
  #   content:
  #     title: "The Team"
  #     subtitle: "Meet our Team Members"
  #     text: |-
  #       ## Welcome
        
  #       This is **markdown content** that you can edit.
        
  #       - Create value
  #       - Add links
  #       - Format text
        
  #       [Learn more](https://example.com)
  #   design:
  #     columns: "1"
 

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: "2"
      
    #   user_groups:
    #     - "Principal Investigators"
    #     - "Researchers"
    #     - "Grad Students"
    #     - "Administration"
    #     - "Visitors"
    #     - "Alumni"
    #   sort_by: "Params.last_name"
    #   sort_ascending: true
    # design:
    #   show_social: true        # icons under each person
    #   show_interests: true     # AI, CL, etc.
    #   show_role: true
    #   show_organizations: true


  - block: team
    id: team
  
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
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
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
