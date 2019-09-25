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
* Ph.D in Political Science --- Washington University in St. Louis (expected May 2020)
* A.M. in Statistics --- Washington University in St. Louis (expected May 2020)
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

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

In Progress
======
  <ul>{% for post in site.papers %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
### Expert:
* R
* Python
* SQL

### Intermediate:
* C++
* BUGS / JAGS / STAN

### Familiar:
* HTML 5
* CSS
* Apache Spark

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
