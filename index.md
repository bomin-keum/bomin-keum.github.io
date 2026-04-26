---
layout: single
author_profile: true
---

<section id="about" markdown="1">
# About 
Hi! I am a PhD student at the International CyberCrime Research Institute in Simon Fraser University. So far, my research focused on online radicalization patterns. Now, I evaluate what works to disrupt these patterns. I do so by engaging in computational methods for distinguishing “Violent” and “Non-Violent” user patterns, conducting a Campbell Systematic Review of radicalization prevention programs, and interviewing formers.
</section>
---

<section id="research" markdown="1">
# Research 

### Published
<ul>
{% for post in site.publications reversed %}
  {% if post.category == 'published' %}
    <li style="margin-bottom: 15px;">{{ post.citation | markdownify }}</li>
  {% endif %}
{% endfor %}
</ul>

### Under Review
<ul>
{% for post in site.publications reversed %}
  {% if post.category == 'under_review' %}
    <li style="margin-bottom: 15px;">{{ post.citation | markdownify }}</li>
  {% endif %}
{% endfor %}
</ul>

### Working Papers
<ul>
{% for post in site.publications reversed %}
  {% if post.category == 'working_paper' %}
    <li style="margin-bottom: 15px;">{{ post.citation | markdownify }}</li>
  {% endif %}
{% endfor %}
</ul>
</section>
---

<section id="cv" markdown="1">
# CV

<div style="margin-top: 20px;">
  <iframe src="/assets/Bomin_Keum_CV.pdf" width="100%" height="1000px" style="border: none;">
    This browser does not support PDFs. Please download the PDF to view it: 
    <a href="/assets/Bomin_Keum_CV.pdf">Download PDF</a>.
  </iframe>
</div>
</section>

---

<section id="contact" markdown="1">
# Contact 
**Email:** [bkeum@sfu.ca](mailto:bkeum@sfu.ca)
</section>
