---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* Ph.D. in Statistics and Bioinformatics, Peking University, China, 2017-2022 
* B.S. in Mathematics and Applied Mathematics, Xi'an Jiaotong University, China, 2013-2017
  * Visiting Student at Georgia Institute of Technology, Atlanta, U.S., 2016
* Special class for the gifted young, Xi'an Jiaotong University, China, 2011-2013

Working Experience
======

* Assistant Professor, School of Mathematics and Statistics, Beijing Institute of Technology, China, 2026-
* Postdoc, International Cancer Institute, Health Science Center, Peking University, China, 2022-2026
  
Publications
======
  <ul>{% assign publications_sorted = site.publications | sort: "date" | reverse %}
{% for post in publications_sorted %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% assign teaching_sorted = site.teaching | sort: "date" | reverse %}
{% for post in teaching_sorted %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% assign talks_sorted = site.talks | sort: "date" | reverse %}
{% for post in talks_sorted %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Service and Leadership
======
* ISCB China Council.
