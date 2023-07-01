---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Doctoral Research Fellow
          company: Faculty of Science, University of Porto
          company_url: 'https://www.dcc.fc.up.pt/site'
          company_logo: org-gc
          location: Porto
          date_start: '2020-08-01'
          date_end: ''
          # description: |2-
          #     Responsibilities include:

          #     * Analysing
          #     * Modelling
          #     * Deploying
        - title: Researcher
          company: INESC TEC - Institute for Systems and Computer Engineering, Technology and Science
          company_url: 'https://www.inesctec.pt/en'
          company_logo: org-x
          location: Porto, Portugal
          date_start: '2019-05-01'
          date_end: ''
          # description: Taught electronic engineering and researched semiconductor physics.
        - title: Co-Founder
          company: HausaNLP
          company_url: 'https://hausanlp.github.io'
          company_logo: org-x
          location: Nigeria
          date_start: '2020-02-12'
        - title: Co-Founder
          company: Arewa Data Science Academy
          company_url: 'https://arewadatascience.org'
          company_logo: org-x
          location: Nigeria
          date_start: '2021-03-05'
        - title: Lecturer
          company: Bayero University , Kano
          company_url: 'https://www.buk.edu.ng/'
          company_logo: org-x
          location: Kano, Nigeria
          date_start: '2012-04-12'
        - title: Lecturer
          company: Saadatu Rimi College of Education
          company_url: ''
          company_logo: org-x
          location: Kano States
          date_start: '2010-10-01'
          date_end: '2012-04-02'
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    id: Publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  #   2: formspree.io
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: shamsuddeen2004@gmail.com
      phone: +351 934 673 685
      # appointment_url: 'https://calendly.com'
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/shmuhammadd'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: 0
        # formspree:
        #   id:
        # netlify:
        #   # Enable CAPTCHA challenge to reduce spam?
        #   captcha: false
    design:
      columns: '2'
  # - block: Note
  #   id: notes
  #   content:
  #     title: Note
  #     subtitle:
  #     text: |-
---
