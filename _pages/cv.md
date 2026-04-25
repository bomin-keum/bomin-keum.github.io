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
* Ph.D in Criminology, Simon Fraser University, 2024 (ongoing)
* M.Phil. in Criminological Research, University of Cambridge, 2023
* B.A. (Hons. Distinction) in Criminology, Simon Fraser University, 2022

Publications
======
### Published (First/Co-author)
<ul>{% for post in site.publications reversed %}{% if post.category == 'manuscripts' %}
  {% include archive-single-cv.html %}
{% endif %}{% endfor %}</ul>

### Under Review
<ul>{% for post in site.publications reversed %}{% if post.category == 'under_review' %}
  {% include archive-single-cv.html %}
{% endif %}{% endfor %}</ul>

### Working Papers
<ul>{% for post in site.publications reversed %}{% if post.category == 'working_paper' %}
  {% include archive-single-cv.html %}
{% endif %}{% endfor %}</ul>
  
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
