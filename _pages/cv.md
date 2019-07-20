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
* Ph.D in Political Science --- Washington University in St. Louis (expected May 2021)
* M.A. in Statistics --- Washington University in St. Louis (expected May 2020)
* M.A. in Political Science --- Washington University in St. Louis  (2018)
* B.A. in Political Science, History, Economics --- University of Miami (2015, *magna cum laud*)

{% comment %}
Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
{% endcomment %}
  
Skills
======
* R
* Python
* SQL
* C++
* BUGS / JAGS / STAN
* HTML 5
* CSS

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
{% comment %}
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
{% endcomment %}
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
