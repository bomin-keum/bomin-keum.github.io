---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
---

# Education
* **Ph.D in Criminology** | Simon Fraser University
* **M.Phil. in Criminological Research** | University of Cambridge

# Publications
### Published
<ul>
{% assign published = site.publications | where: "category", "published" %}
{% for post in published reversed %}
  <li>{{ post.citation | markdownify }}</li>
{% endfor %}
</ul>

### Under Review
<ul>
{% assign reviews = site.publications | where: "category", "under_review" %}
{% for post in reviews %}
  <li>{{ post.citation | markdownify }}</li>
{% endfor %}
</ul>
