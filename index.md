---
layout: single
---

# About 
{: #about}
Hi! I am a PhD student at the International CyberCrime Research Institute in Simon Fraser University. So far, my research focused on online radicalization patterns. Now, I evaluate what works to disrupt these patterns. I do so by engaging in computational methods for distinguishing “Violent” and “Non-Violent” user patterns, conducting a Campbell Systematic Review of radicalization prevention programs, and interviewing formers.

---

# Research 
{: #research}

### Published
{% for post in site.publications reversed %}
  {% if post.category == 'published' %}
* {{ post.citation | markdownify }}
  {% endif %}
{% endfor %}

### Under Review
{% for post in site.publications reversed %}
  {% if post.category == 'under_review' %}
* {{ post.citation | markdownify }}
  {% endif %}
{% endfor %}

### Working Papers
{% for post in site.publications reversed %}
  {% if post.category == 'working_paper' %}
* {{ post.citation | markdownify }}
  {% endif %}
{% endfor %}

---

# CV
{: #cv}

<div style="margin-top: 20px;">
  <iframe src="/assets/Bomin_Keum_CV.pdf" width="100%" height="1000px" style="border: none;">
    This browser does not support PDFs. Please download the PDF to view it: 
    <a href="/assets/Bomin_Keum_CV.pdf">Download PDF</a>.
  </iframe>
</div>

---

# Contact 
{: #contact}
**Email:** [bkeum@sfu.ca](mailto:bkeum@sfu.ca)
