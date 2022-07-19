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
  - title: Full Stack Developer
    company: Network Optimization Lab, NCTU
    company_url: ''
    company_logo: nctu
    location: Hsinchu, Taiwan
    date_start: '2021-07-01'
    date_end: '2022-06-30'
    description: |2-
        - Led a team of 20+ graduate students and developed a deep learning network for high-speed and tiny objects tracking to analyze badminton contests and the performance of national athletes of the 2020 Tokyo Olympics
        - Reduced the average data processing time from one day to three hours by integrating backend architectures and
        designing RESTful APIs with WSGI HTTP Server, Flask, Apache, and MySQL
        - Refactored the frontend using React.js, Redux; cooperated with the designer to redesign the website workflow
        - Implemented authentication workflow with Google OAuth by using JWT and Flask Session
        - Won 2020 Future Tech Award among 600+ teams of Ministry of Science and Technology

  - title: Security Testing Intern
    company: Trend Micro Inc.
    company_url: 'https://www.trendmicro.com/en_us/business.html'
    company_logo: Trend-Micro-Logo
    location: Hsinchu, Taiwan
    date_start: '2019-09-01'
    date_end: '2019-12-31'
    description: |2-
      - Introduced 18+ testing features for multiple platforms of company software to ensure all products’ performance, security, and log collection
      - Utilized Packet Player and Shell scripts to monitor the throughput and detection rate of spyware, and virus

  - title: IoT Frontend Intern
    company: 3drens Startup Company
    company_url: 'http://www.3drens.com/'
    company_logo: 3drens
    location: Taipei, Taiwan
    date_start: '2019-07-01'
    date_end: '2019-08-31'
    description: |2-
      - Visualized E-scooters’ real-time GPS positions on Google Maps with IoT devices, Maps JavaScript API, React.js
      - Developed the frontend of Content Management System (CMS) such as Geo-fencing, Heatmap, Dashboard
      - Solved cross-platform (iOS, Android) authentication problems with Facebook OAuth and In-App browser

  - title: Software-Defined Network (SDN) Intern
    company: D-Link NCTU Joint Research Center
    company_url: 'https://www.dlink.com/en/consumer'
    company_logo: D-Link-Logo.wine
    location: Hsinchu, Taiwan
    date_start: '2019-01-01'
    date_end: '2019-06-30'
    description: |2-
      - Proposed and achieved an SDN-IP architecture by emulating BGP routing and realistic virtual networks on virtual machines with ONOS (SDN controller), Quagga, Mininet, and Python
      - Engineered different network topology to verify 30+ functions of flow and group tables on SDN-enabled switches

design:
  columns: '1'
---
