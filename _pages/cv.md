---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download a PDF copy of my CV [here](/Meshhal_cv_Feb2022.pdf).

Education
======
* PhD in Computational Chemical Physics, Universität Rostock (Germany), 2023 (expected)
* MSc in Physical Chemistry, Menofia University (Egypt), 2019
* BSc in Chemistry,  Menofia University (Egypt), 2014
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
