---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Python
          description: 80%
          icon: python
          icon_pack: fab
        - name: MS-office
          description: 90%
          icon: microsoft
          icon_pack: fab
        - name: Water Treatment
          icon: tank-water
          icon_pack: fab
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: May 2022
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Product Development Engineer
          company: Flow Loop
          company_url: ''
          company_logo: FL
          location: Copenhagen
          date_start: '2022-05-21'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Water quality
              * Water disinfection
              * Water reuse
        - title: PhD in Microbiology applied to Water Treatment
          company: Novozymes
          company_url: ''
          company_logo: novozymes
          location: Copenhagen
          date_start: '2019-02-01'
          date_end: '2022-03-31'
          description:  |2-
              Project aiming at optmizing biological water treatment through biotechnology
              * Design of water treatment units at pilot and field scale (Nitrogen removal)
              * Determined sludge microbial composition
              * Injection of microbes to boost treatment efficiency
              * Water quality analysis (Carbon, Nitrogen, Phosphorous)
              * Data analysis with R and Python (Statistics and Machine Learning)
              * Leadership of technicians and junior students during various projects at Aarhus University and Novozymes
              * Student advisor, lecturing of B.S. students and supervision of M.S. students
              * Published 8 peer-reviewed scientific articles
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-02-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Data Analyst with Python
          url: ''
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-02-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Python Programmer
          url: ''
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Data Scientist with Python
          url: ''
    design:
      columns: '2'
  - block: collection
    id: education
    content:
      title: Education
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - education
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: collection
    id: prof_experience
    content:
      title: Professional experience
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - prof_experience
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: collection
    id: interests
    content:
      title: Interests
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - interests
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Water filtration
          tag: Water filtration
        - name: Water disinfection
          tag: Water disinfection
        - name: Water reuse
          tag: Water reuse
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    id: publication
    content:
      title: Publications
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
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Leave me a message
      # Contact (add or remove contact options as necessary)
      email: ajeglot@gmail.com
      phone: 
      appointment_url: 'https://calendly.com/ajeglot/30min'
#      address:
#        street: 
#        city: 
#        region: 
#        postcode: ''
#        country: 
#        country_code: 
#      directions: 
#      office_hours:
#        - ''
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: ''
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: ''
      # Automatically link email and phone or display as text?
#      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
