---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-03-03
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Economist
          company: U.S. Department of the Treasury
          company_url: ''
          company_logo: ''
          location: Washington, DC
          date_start: '2022-10-01'
          date_end: ''
        - title: Associate Instructor
          company: University of California, Davis
          company_url: ''
          company_logo: ''
          location: Davis, CA
          date_start: '2022-01-01'
          date_end: '2022-03-01'
    design:
      columns: '2'
  - block: collection
    id: research
    content:
      title: Research
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: community/compact_custom
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_start: '2022-01-01'
          organization: Washington Center for Equitable Growth
          organization_url: https://equitablegrowth.org/
          title: 'Doctoral Grant'
        - date_start: '2014-09-01'
          organization: University of California, Davis
          title: 'Graduate Fellowship'
        - date_start: '2014-06-01'
          organization: Binghamton University
          title: 'Economics Faculty Award for Excellence in Economics'
        - date_start: '2014-06-01'
          organization: Binghamton University
          title: 'J.C. Liu Prize for Outstanding Honors Thesis'
    design:
      columns: '2'
  ---