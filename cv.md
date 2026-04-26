---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
---

Education
======
* Ph.D in Criminology, Simon Fraser University, 2024 (ongoing)
* M.Phil. in Criminological Research, University of Cambridge, 2024
* B.A. (Hons. Distinction) in Criminology, Simon Fraser University, 2022

Publications
======
{% for post in site.publications reversed %}
  {% if post.category == "published" %}
* {{ post.citation }}
  {% endif %}
{% endfor %}

### Under Review
{% for post in site.publications reversed %}
  {% if post.category == "under_review" %}
* {{ post.citation }}
  {% endif %}
{% endfor %}

### Working Papers
{% for post in site.publications reversed %}
  {% if post.category == "working_paper" %}
* {{ post.citation }}
  {% endif %}
{% endfor %}
  
Talks
======
{% for post in site.talks reversed %}
  {% if post.category == "talks" %}
* {{ post.citation }}
  {% endif %}
{% endfor %}
  
Teaching
======
{% for post in site.teaching reversed %}
  {% if post.category == "teaching" %}
* {{ post.citation }}
  {% endif %}
{% endfor %}

Grants
======
* $10,000 Canadian Network for Security & Extremism, **Author/PI**,  2026
  * Project: "Gendered Pathways to Nonviolence: A Scoping Review of Protective Factors"
* $93,577 Department of Homeland Security, **Research Assistant**, 2024
  * Project: "Interventions to Prevent Cognitive and Behavioural Radicalization: A Multilevel Meta-analysis"
* $874,170 Defence Sciences Division of Public Works and Government Services Canada, **Research Assistant**, 2022
  * Project: "The Dark Crawler: Combating Disinformation Warfare with Artificial Intelligence"

Honours and Awards
======
* $6,500 Criminology Graduate Fellowship, 2026
* $5,000 Travel & Research Award, 2026 *fund: Behavioural and Social Science Conference presentation at Cardiff University (Cardiff, UK)
* $2,239 Travel & Research Award, 2025 *fund: VOX-Pol Next-Gen Conference at Charles University (Prague, Czech Republic)
* $6,058 PhD Research Scholarship, 2025
* $3,500 Criminology Graduate Fellowship, 2025
* $2,650 Travel & Research Award, 2025 *fund: C-REX & VOX-Pol Extremism Research Workshop at University of Oslo (Oslo, Norway)
* $499 GSS Professional Development Grant, 2025
* $1,836 PhD Research Scholarship, 2024

Service
======
* Cambridge BroBono Project, organizer, “Meeting at the Crossroads: Aligning Global Agendas to End Exploitation”, 2024
* Cambridge, co-organizer, "Misinformation Hackathon with CRASSH" (a UK-based policy think tank), 2024
* Cambridge, organizer and MOC, "Decolonizing Criminology Classrooms: How Do We Move Beyond Rhetoric?" 2024

[Download Full CV (PDF)](/assets/Bomin_Keum_CV.pdf){: .btn .btn--info}
