---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Work Experience
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
  - title: Research Assistant
    company: Network Optimization Lab, NCTU
    company_url: ''
    company_logo: nctu
    location: Hsinchu, Taiwan
    date_start: '2021-07-01'
    date_end: ''
    description: |2-
        - Won 2020 Future Tech Award among 600+ teams of Ministry of Science and Technology.
        - Led 20 graduate students research team to develop TrackNet for high-speed tiny object tracking applications.
        - Integrated and modularized backend architecture using WSGI HTTP Server, Flask, Apache, and MySQL.
        - Enhanced software security by preventing SQL injection, cross-site scripting and CSRF.

  - title: Testing Intern
    company: Trend Micro Inc.
    company_url: 'https://www.trendmicro.com/en_us/business.html'
    company_logo: Trend-Micro-Logo
    location: Hsinchu, Taiwan
    date_start: '2019-09-01'
    date_end: '2019-12-31'
    description: |2-
      - Built 18 testing features to test the throughput of routers and visualized by nmon analyser.
      - Utilized packet players andshell scriptsto monitor the detection rate of spyware, virus, and vulnerability.

  - title: IOT Front-End Intern
    company: 3drens Startup Company
    company_url: 'http://www.3drens.com/'
    company_logo: 3drens
    location: Taipei, Taiwan
    date_start: '2019-07-01'
    date_end: '2019-08-31'
    description: |2-
      - Developed the CMS front-end and App service via ReactJS and Redux and Typescript.
      - Leveraged IoT devices to track E-scooters’ real-time GPS position and visualized via Maps JavaScript API.
      - Solved 63 tasks in two months through developing features such as Geo-fencing, heat map, and dashboard.

  - title: SDN Intern
    company: D-Link NCTU Joint Research Center
    company_url: 'https://www.dlink.com/en/consumer'
    company_logo: D-Link-Logo.wine
    location: Hsinchu, Taiwan
    date_start: '2019-01-01'
    date_end: '2019-06-30'
    description: |2-
      - Built SDN-IP application to talk BGP with routers to exchange traffic between different external ASes.
      - Emulated BGP routing and realistic virtual networks by Quagga and Mininet.
      - Verified 30+ functions of the flow, group, and meter tables of switches in different SDNs.

design:
  columns: '1'
---
