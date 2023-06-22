---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: bruno
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      # default_button_index: 0
      # # Filter toolbar (optional).
      # # Add or remove as many filters (`filter_button` instances) as you like.
      # # To show all items, set `tag` to "*".
      # # To filter by a specific tag, set `tag` to an existing tag name.
      # # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Regression
      #     tag: Regression Analysis
      #   - name: Classification
      #     tag: Classification
      #   - name: Clustering
      #     tag: Clustering
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: Python
          description: 
          icon: 
          icon_pack: fab
        - name: SQL
          description: 
          icon: 
          icon_pack: fab
        - name: Tableau
          description: 
          icon: 
          icon_pack: fab
        - name: pandas
          description: 
          icon: 
          icon_pack: fab
        - name: scikit-learn
          description: 
          icon: 
          icon_pack: fab
        - name: Data Analysis
          description: 
          icon: 
          icon_pack: fas
        - name: Exploratory Data Analysis (EDA)
          description: 
          icon: 
          icon_pack: fas
        - name: Data Visualization
          description: 
          icon: 
          icon_pack: fas
        - name: Machine Learning
          description: Regression, Classification, Clustering
          icon: 
          icon_pack: fas
        - name: Predictive Modelling
          description:
          icon: 
          icon_pack: fas
        - name: Statistical Analysis
          description: 
          icon: 
          icon_pack: fas
        - name: A/B Testing
          description: 
          icon: 
          icon_pack: fas
        - name: Deep Learning
          description: TensorFlow, PyTorch
          icon: 
          icon_pack: fas
        - name: Problem-Solving
          description: 
          icon: 
          icon_pack: fas
        - name: Effective Written Communication
          description: 
          icon: 
          icon_pack: fas
  - block: experience
    id: exp
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
        - title: Associate Researcher (PhD student)
          company: Brazilian Center for Research in Energy and Materials (CNPEM)
          company_url: ''
          company_logo: cnpem
          location: Campinas, Brazil
          date_start: '2019-02-01'
          date_end: ''
          description: |2-
              * Collaboration with experimental scientists.
              * Data Mining and Statistical Analysis of experimental data.
              * Insights from machine learning models (regression and classification).
              * Interpretation of time series data using clustering.
              * Data visualization and presentation.
        - title: Visiting Research Fellow (PhD student)
          company: Trinity College Dublin
          company_url: ''
          company_logo: tcd
          location: Dublin, Ireland
          date_start: '2022-02-04'
          date_end: '2023-02-03'
          description: Machine learning and Predictive modelling for two-dimensional materials' properties at the Computational Spintronics Group, led by Stefano Sanvito.
    design:
      columns: '2'
  - block: accomplishments
    id: certificates
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      # title: 'Accomplish&shy;ments'
      title: 'Certificates'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/FTL8GUV5SSR4
          date_end: ''
          date_start: '2023-06-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Google Advanced Data Analytics
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/YMY6S9D6VRRD
          date_end: ''
          date_start: '2023-05-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: "SQL for Data Science"
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/MQDJCP9CSKP6
          date_end: ''
          date_start: '2023-05-06'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: The Nuts and Bolts of Machine Learning
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/ESQ5E7RD4KAX
          date_end: ''
          date_start: '2023-05-02'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Foundations of Data Science
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/TUTEQANNQ7YH
          date_end: ''
          date_start: '2023-05-03'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: "Go Beyond the Numbers: Translate Data into Insights"
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/NWWGV5QNAXLW
          date_end: ''
          date_start: '2023-05-05'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: "Regression Analysis: Simplify Complex Data Relationships"
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/HT9AU62543JS
          date_end: ''
          date_start: '2023-05-04'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: "The Power of Statistics"
          url: ''
        # - certificate_url: https://www.edx.org
        #   date_end: ''
        #   date_start: '2017-10-01'
        #   description: ''
        #   organization: edX
        #   organization_url: https://www.edx.org
        #   title: A Hands-on Introduction to Engineering Simulations
        #   url: ''
    design:
      columns: '2'
  - block: collection
    id: publications
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
      view: list
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to send me an email
      # Contact (add or remove contact options as necessary)
      email: bfocassio@gmail.com
      phone: +55 11 9 9674 3180
      # Automatically link email and phone or display as text?
      autolink: true
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
