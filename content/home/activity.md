---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 118

title: Extracurricular Activity
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Open Source Community - NCTU+
    company: NCTU
    company_url: ''
    company_logo: plus
    location: Hsinchu, Taiwan
    date_start: '2017-07-01'
    date_end: '2019-06-30'
    description: |2-
      - Led a frontend team of 10+ people to develop a website for course planning, course advising, and GPA calculation
      - Achieved a 95%+ (5000+) usage of NCTU students, obtaining annual funds from Alumni Association

  - title: BambooFox CTF Club
    company: NCTU
    company_url: ''
    company_logo: ''
    location: Hsinchu, Taiwan
    date_start: '2020-09-01'
    date_end: '2020-12-31'
    description: |2-
      - Found and attacked website vulnerabilities by CSRF, SQL injection, Local File Inclusion.
      - Implemented padding oracle attack on block cipher mode.

design:
  columns: '2'
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 5
---
