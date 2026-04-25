---
layout: single
author_profile: true
permalink: /
---

<a name="about"></a>
# About

Hi! I am a PhD student at the International CyberCrime Research Institute in Simon Fraser University. So far, my research focused on online radicalization patterns. Now, I evaluate what works to disrupt these patterns. I do so by engaging in computational methods for distinguishing “Violent” and “Non-Violent” user patterns, conducting a Campbell Systematic Review of radicalization prevention programs, and interviewing formers.

---

<a name="research"></a>
# Research

### Published
<ul>{% for post in site.publications reversed %}{% if post.category == 'manuscripts' %}
  {% include archive-single-cv.html %}
{% endif %}{% endfor %}</ul>

### Under Review
<ul>{% for post in site.publications reversed %}{% if post.category == 'under_review' %}
  {% include archive-single-cv.html %}
{% endif %}{% endfor %}</ul>

---

<a name="cv"></a>
# CV

[Download CV as PDF](/assets/Bomin_Keum_CV.pdf){: .btn .btn--info}

<iframe src="/assets/Bomin_Keum_CV.pdf" width="100%" height="800px"></iframe>

---

<a name="contact"></a>
# Contact
**Email:** [bkeum@sfu.ca](mailto:bkeum@sfu.ca)
**Affiliation:** International Cybercrime Research Institute, SFU
