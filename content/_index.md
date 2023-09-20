---
# Leave the homepage title empty to use the site title
title: Hongshen Zhu
date: 2023-09-19
type: landing


<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-2C0N6QHN50"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-2C0N6QHN50');
</script>


sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Appointments
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Aug 2023
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Global China Postdoctoral Fellow
          company: East Asia Center, University of Virginia
          company_url: ''
          company_logo:
          location: Virginia
          date_start: '2023-08-22'
          date_end: ''
          description: 
        - title: Postdoctoral Fellow
          company: University of Pennsylvania
          company_url: ''
          company_logo:
          location: Pennsylvania
          date_start: '2022-08-01'
          date_end: '2023-07-31'
          description: 
    design:
      columns: '2'
---