---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style type="text/css" rel="stylesheet">
.row{clear:both}

.column{
    width: 50%;
    float: left;
}
</style>

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

Skills
======
<div class="row">
    <div class="column">
        <h2>Expert:</h2>
        <ul>
            <li>R</li>
            <li>Python</li>
            <li>SQL</li>
        </ul>
    </div>
    <div class="column">
        <h2>Intermediate:</h2>
        <ul>
            <li>C++</li>
            <li>JAGS / STAN</li>
        </ul>
    </div>
    <div class="column">
        <h2>Familiar:</h2>
        <ul>
            <li>HTML 5</li>
            <li>CSS</li>
            <li>Apache Spark</li>
        </ul>
    </div>
</div>

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
