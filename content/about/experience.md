---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Engineer
    company: Amplify
    company_url: https://amplify.com/
    company_logo: amplify
    location: New York (Remote)
    date_start: '2022-08-01'
    date_end: '2023-10-01'
    description: |2-
        * Advanced the development of 6 microservice applications on an agile, back-end team.
        * Designed and engineered four REST API endpoints using the Serverless and FastAPI frameworks with Python to build an internal troubleshooting tool. 
        * Implemented documentation-as-code practices to expand API documentation in Swagger, facilitating easier access and understanding for cross-functional teams. 
        * Enhanced team collaboration and knowledge sharing by creating software tutorials and documentation for new features, expanding the team's Google Drive repository.
        * Authored process documentation for the 1EdTech certification process for compliance with the Learning Tools Interoperability (LTI) standard.

  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '1'
---
