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
  - title: Software Development Engineer Intern
    company: Amazon LLC
    company_url: ''
    company_logo: amazon
    location: Sunnyvale, CA
    date_start: '2023-05-30'
    date_end: '2023-08-18'
    description: |2-
        - Designed an overall architecture that integrates an internal service with a non-blocking network I/O system in our
          tier-1 serverless platform, running over 120K+ production hosts, used by over 500+ teams
        - Composed the asynchronous calls and event-based programs following observer pattern with RxJava
        - Implemented an authentication and timeout mechanism using an OAuth-based solution
        - Coordinated and unified the behavior of similar external service calls to make them scalable, reusable, and tolerant of remote fault by using singleton pattern and dependency injection
        - Designed, built, and tested the architecture with Java (OOD, Junit), Git, Linux, and internal tools

  - title: Full Stack Developer
    company: Network Optimization Lab, NCTU
    company_url: ''
    company_logo: nctu
    location: Hsinchu, Taiwan
    date_start: '2021-07-01'
    date_end: '2022-06-30'
    description: |2-
        - Led a team of 20+ graduate students to analyze badminton contests and the performance of national athletes of the 2020 Tokyo Olympics
        - Reduced 87.5% average data processing time by integrating backend architectures and designing RESTful APIs with WSGI HTTP Server, Flask, Apache, and MySQL
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
      - Introduced 18+ testing features to ensure company products’ performance, security, and log collection
      - Utilized packet player and shell scripts to monitor the throughput and configured network devices, including fiber cables, switches, routers, firewalls, and QoS

  - title: IoT Frontend Intern
    company: 3drens Startup Company
    company_url: 'http://www.3drens.com/'
    company_logo: 3drens
    location: Taipei, Taiwan
    date_start: '2019-07-01'
    date_end: '2019-08-31'
    description: |2-
      - Leveraged IoT devices to track E-scooters’ GPS positions and visualized via Maps API, React.js, and Redux.
      - Developed the front-end of Content Management System (CMS) such as Geo-fencing, Heatmap, and Dashboard
      - Solved cross-platform (iOS, Android) authentication problems of Facebook OAuth and In-App browser

  - title: Software-Defined Network (SDN) Intern
    company: D-Link NCTU Joint Research Center
    company_url: 'https://www.dlink.com/en/consumer'
    company_logo: D-Link-Logo.wine
    location: Hsinchu, Taiwan
    date_start: '2019-01-01'
    date_end: '2019-06-30'
    description: |2-
      - Proposed and achieved an SDN-IP architecture by emulating BGP routing and realistic virtual networks on virtual machines and SDN-enabled switches using ONOS (SDN controller), Quagga, Mininet, and Python
      - Engineered different network topology to verify 30+ functions of flow and group tables on SDN-enabled switches, including Ethernet, IPv4, IPv6, TCP, UDP, HTTP, VLAN, multicast, and L2 rewrite

design:
  columns: '1'
---
