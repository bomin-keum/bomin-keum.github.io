---
layout: single
title: "About"
header:
  overlay_filter: 0.5
---

{: #about}
Hi! I am a PhD student at the International CyberCrime Research Institute in Simon Fraser University. So far, my research focused on online radicalization patterns. Now, I evaluate what works to disrupt those patterns. I do so by engaging in computational methods for distinguishing “Violent” and “Non-Violent” user patterns, conducting a Campbell Systematic Review of radicalization prevention programs, and interviewing formers to identify intervention targets for supporting those struggling in the process of navigating exit.

---

# Research 
{: #research}

### Published
{% assign published = site.publications | where: "category", "published" %}
{% for post in published reversed %}
* {{ post.citation | markdownify }}
{% endfor %}

### Under Review
{% assign reviews = site.publications | where: "category", "under_review" %}
{% for post in reviews reversed %}
* {{ post.citation | markdownify }}
{% endfor %}

### Working Papers
{% assign reviews = site.publications | where: "category", "working_paper" %}
{% for post in reviews reversed %}
* {{ post.citation | markdownify }}
{% endfor %}

### Talks 
Presenter, <b>Behavioural and Social Sciences in Security Conference (BASS26)</b>, Cardiff, 2026
Presenter, <b>CONDUITS Modulations Conference</b>, Burnaby, 2026
Guest Lecturer, <b>University of Sussex</b>, Sussex, 2026 **for Dr. Suraj Lakhani’s undergraduate course in Sociology,
Law, and Terrorism
Presenter, <b>Canadian Network of Security and Extremism Studies (CANSES)</b>, Burnaby, 2026
Guest Lecturer, <b>University of Waterloo</b>, Waterloo, 2026 **for Dr. Karmvir Padda’s 4th year undergraduate course
SOC422: Violent Extremism and Terrorism
Presenter, <b>VOX-Pol Next Gen Conference</b>, Prague, 2025
Presenter, <b>Australia Violent Extremism and Radicalization to Terrorism (AVERT)</b>, Melbourne, 2024
Presenter, <b>British Society of Criminology (BSC)</b>, Glasgow, 2024
Presenter, <b>Cambridge Cybercrime Centre (CCC)</b>, Cambridge, 2024
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
