---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, City University of Hong Kong, 2021
* M.S. in Computer Application Technology, Peking University, 2018
* B.S. in Electronical Engineering (Hornor's Program), China Agricultural University, 2015

Work experience
======
* 2021 Oct. -- 2024 Aug.: Postdoc Researcher
  * City University of Hong Kong
  * Supervisor: Prof. Shiqi Wang 
  
Research interests
======
* Video Compression
* AI-based Compression

Publications
======
  <ul>{% [for post in site.publications reversed](https://scholar.google.com/citations?user=6vnhEIgAAAAJ&hl=zh-CN) %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
