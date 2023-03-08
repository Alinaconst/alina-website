---
# Leave the homepage title empty to use the site title
title: Home
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:

  - block: experience
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
        - title: Technical Recruiter (AI & ML)
          company: Apple
          # company_url: 'https://apple.com'
          # company_logo: org-gc
          location: London, United Kingdom
          date_start: '2020-02-01'
          date_end: ''
          description: |2-
              * Scaling Software Engineering & AIML teams in Europe (Zürich, Cambridge, Barcelona, Paris, Münich). Areas covered: Health AI, Computer Vision, NLP, Machine Learning Research, Data engineering, Siri teams (translation, annotation, search, visual search)
              * Diversity champion: highest number of diverse hires in region (60% in FY22)
              * Represented Apple @ AI conferences: NeurIPS, ICCV, CVPR, ECCV
              * Provided outstanding candidate experience: top ratings from candidates
              * Successfully and consistently delivered in a fast paced, fast changing environment with aggressive targets: averaging 50+ hires per year
              * Partnered with HR and other stakeholders to deliver great complexity of internal transfers between US (Cupertino) and Europe
              * Developed and maintained quality talent pipelines through extensive sourcing and market mapping
              * Provided comprehensive, data orientated advice to hiring managers

        - title: Technical Recruiter
          company: Education First
          # company_url: ''
          # company_logo: org-x
          location: London, United Kingdom
          date_start: '2018-07-01'
          date_end: '2020-01-01'
          description: |2-
            * Scaling Engineering teams in Europe & China (Lucerne, London, Shanghai)
            * Interest in engineers from the Gaming and Education sector
            * Roles covered: full-stack, front-end, back-end engineering, interns
            * Setting up hiring strategies between Shanghai and London

        - title: Technical Sourcing Recruiter
          company: Microsoft & Microsoft Research
          company_url: ''
          # company_logo: org-x
          location: London, United Kingdom
          date_start: '2017-02-01'
          date_end: '2018-06-01'
          description: |2-
            * Scaling engineering teams in Europe (London, Prague, Copenhagen, Cambridge)
            * Diversity champion: 55% diversity rate across Europe
            * Setting up recruitment fairs and networking events across Europe

        - title: Technical Sourcer
          company: Google
          company_url: ''
          # company_logo: org-x
          location: London, United Kingdom
          date_start: '2016-04-01'
          date_end: '2017-12-01'
          description: |2-
            * Technical Sourcer for SWE and SRE roles across Europe (Zürich, London)
            * Participated to international hiring events & career fairs

    design:
      columns: '2'


  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: 6
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
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


  - block: contact
    id: contact
    content:
      title: Contact
      # subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: alinacon@gmail.com
      # phone: +44 (0)7890395038
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
      contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM Me
        #   link: 'https://twitter.com/Twitter'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
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
