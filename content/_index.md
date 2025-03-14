---
# Leave the homepage title empty to use the site title
title: ''
type: landing

sections:
  # =========== BIO =========
  # ============================   
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin


  # =========== SKILLS =========
  # ============================        
  - block: skills
    id: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '2'


  # =========== EXPERIENCE======
  # ============================        
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: 6
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

            
        - title: Senior Recruiter (Software, Engineering & Artificial Intelligence)
          company: Mistral AI
          # company_url: 'https://apple.com'
          company_logo: mistral2
          location: London, United Kingdom
          date_start: '2024-12-01'
          description: |2-

            * First Recruiter in London UK (Contract)
            * Hiring AI, LLMs, Science, Engineering experts across Paris, London and Palo Alto.
            * Mistral AI: are providing customisable AI solutions to comapnies all over the world. Mistral AI is founded by scientists from Google Deep Mind and Meta to provide open-source generative AI models to empower developers and enterprises to build the future.

        - title: Senior Technical Recruiter (Software & Artificial Intelligence)
          company: Apple 
          # company_url: 'https://apple.com'
          company_logo: apple
          location: London, United Kingdom
          date_start: '2020-02-01'
          date_end: '2024-09-30'
          description: |2-
            
              * Drove the expansion of Artificial Intelligence and Software Engineering teams across Europe, establishing hubs in Zurich, Cambridge, Barcelona, Paris, and Munich.
              * Achieved a regional record of 60% diverse hires in FY22/23, demonstrating a commitment to building inclusive and representative teams.
              * Represented Apple at prestigious AI, Computer Vision and Speech conferences, including NeurIPS, ICCV, CVPR, and ECCV.
              * Engaged with C-Suite leaders in Europe and United States
              * Thrived in a fast-paced, dynamic environment, consistently exceeding aggressive hiring targets, averaging over 40 hires annually, highlighting my ability to deliver results under pressure.
              * Collaborating effectively with US peers and other stakeholders to facilitate complex internal transfers between Apple's Cupertino headquarters and European offices, demonstrating my ability to navigate complex organizational structures and achieve shared goals.
              * Cultivated and maintained  robust talent pipelines through extensive sourcing and market mapping initiatives,ensuring a steady supply of qualified candidates to meet the evolving needs of the company.
              * Provided data-driven, comprehensive hiring guidance to hiring managers, empowering them to make informed decisions.

        - title: Technical Recruiter
          company: Education First
          # company_url: ''
          company_logo: ef
          location: London, United Kingdom
          date_start: '2018-07-01'
          date_end: '2020-01-01'
          description: |2-
            * Instrumental in expanding Engineering teams across Europe and China, establishing offices in Lucerne, London, and Shanghai.
            * Possessed a keen focus on recruiting engineers from the Gaming and Education sectors.
            * Successfully filled a diverse range of roles, encompassing full-stack, front-end, back-end engineering, and internships.
            * Strategically formulated hiring processes between Shanghai and London, fostering seamless collaboration and talent acquisition.

        - title: Technical Sourcing Recruiter (Contract)
          company: Microsoft & Microsoft Research
          # company_url: ''
          company_logo: windows
          location: London, United Kingdom
          date_start: '2017-02-01'
          date_end: '2018-06-01'
          description: |2-
            * Played a pivotal role in expanding engineering teams across Europe, establishing hubs in London, Prague,Copenhagen, and Cambridge.
            * Spearheaded diversity initiatives, achieving an impressive 55% diversity rate across Europe.
            * Organized and executed a series of recruitment fairs and networking events throughout Europe, fostering connections with top talent.

        - title: Technical Sourcer (Contract)
          company: Google
          # company_url: ''
          company_logo: google
          location: London, United Kingdom
          date_start: '2016-04-01'
          date_end: '2017-12-01'
          description: |2-
            * Effectively sourced technical talent for SWE and SRE roles across Europe, including Zurich, London, and Dublin.
            * Actively participated in international hiring events and career fairs, expanding Google's reach and attracting top candidates.

    design:
      columns: '2'

  # ===== ACCOMPLICEMENTS ======
  # ============================        
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  # 
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         icon: coursera
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  # 
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         icon: edx
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  # 
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         icon: datacamp
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  # 
  #   design:
  #     columns: '2'

  # ========= EDUCATION ========
  # ============================    
  - block: experience
    id: education
    content:
      title: Education & Certifications
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: 6
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

        - title: Certifications
          company: Techmap
          company_url: 'https://www.techmap.app/'
          # company_logo: org-gc
          # location: Surrey, United Kingdom
          date_start: '2024-07-01'
          date_end: '2024-07-15'
          description: 
             "TechMap Certification for Technical Recruiters"
    
        - title: Online Courses
          # company: Coursera
          # company_url: 'https://apple.com'
          # company_logo: org-gc
          # location: Surrey, United Kingdom
          date_start: '2023-01-01'
          date_end: '2023-12-31'
          description: 
             "Artificial Intelligence for Everyone by Andrew Ng (Coursera)\n\n
             Artificial Intelligence: Business Strategies and Applications (Berkeley ExecEd)\n\n
             AI and Machine Learning for Business (Udemy)"

        - title: MSc International Human Resource Management
          company: Royal Holloway, University of London
          # company_url: 'https://apple.com'
          # company_logo: org-gc
          location: Surrey, United Kingdom
          date_start: '2012-01-01'
          date_end: '2013-01-01'
          description: |2-

        - title: MA Economics
          company: Academy of Economic Studies of Bucharest
          # company_url: 'https://apple.com'
          # company_logo: org-gc
          location: Bucharest, Romania
          date_start: '2010-02-01'
          date_end: '2012-02-01'
          description: |2-

        - title: Erasmus Scholarship
          company: Bifröst University
          # company_url: 'https://apple.com'
          # company_logo: org-gc
          location: Iceland
          date_start: '2009-02-01'
          date_end: '2009-02-01'
          description: |2-

        - title: BSc Management
          company: Romanian American University
          # company_url: 'https://apple.com'
          # company_logo: org-gc
          location: Bucharest, Romania
          date_start: '2007-02-01'
          date_end: '2009-02-01'
          description: |2-

    design:
      columns: '2'

  # ======== INTERESTS =========
  # ============================    
  - block: contact
    id: interests
    content:
      title: "Interests"
      # subtitle:
      text: "Reading, Travelling, Hiking, Photography"
    design:
      columns: '2'


  # ======= RECENT POSTS =======
  # ============================ 
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

  # =========== PORTFOLIO ======
  # ============================    
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
  
  # ========= GALLERY ==========
  # ============================    
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  
  # == FEATURED PUBLICATIONS ===
  # ============================ 
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
  
  # === RECENT PUBLICATIONS ====
  # ============================ 
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation

  # ======== TAG CLOUD =========
  # ============================ 
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'

  # ======== CONTACT ===========
  # ============================ 
  - block: contact
    id: contact
    content:
      title: Contact
      # subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: alinaconsta8@gmail.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697'  
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
