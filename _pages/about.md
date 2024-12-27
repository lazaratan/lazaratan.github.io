---
layout: about
title: About
permalink: /
subtitle: I am a Ph.D. Candidate at the <a href='https://www.utoronto.ca/'>University of Toronto</a> in <a href='https://www.ece.utoronto.ca/'>The Department of Electrical & Computer Engineering</a> and the <a href='https://vectorinstitute.ai/'>Vector Institute</a>.

profile:
  align: right
  image: laz_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: l.atanackovic@mail.utoronto.ca
    #<p>555 your office number</p>
    #<p>123 your address street</p>
    #<p>Your City, State 12345</p>

social: true # includes social icons at the bottom of the page
news: false # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
---

I am a member of the <a href='https://psi.toronto.edu/'>Probabilistic and Statistical Inference Group</a> supervised by <a href='https://psi.toronto.edu/~frey/'>Brendan Frey</a> and co-supervised by <a href='https://wanglab.ai/people.html'>Bo Wang</a>. Previously, I was a research intern at <a href='https://www.recursion.com/'>Recursion Pharmaceuticals</a> / <a href='https://www.valencelabs.com/'>Valence Labs</a>, <a href='https://www.deepgenomics.com/'>Deep Genomics</a>, and <a href='https://mila.quebec/en/'>Mila - Quebec AI Institute</a>.

My research focuses on developing machine learning methods for deciphering and modelling complex dynamical systems from data, with a particular focus on computational biology and biological systems. My interests include (but are not limited to) generative modelling (flows and diffusion), dynamical systems, causality, single-cell biology, and proteins.

Feel free to contact me for collaborations or if you have any questions about my work!

---

### Selected Publications
{% for paper in site.bib %}
  {% if paper.selected == true %}
    <p><strong>{{ paper.title }}</strong></p>
    <p>{{ paper.author }} - <a href="{{ paper.url }}">Read More</a></p>
  {% endif %}
{% endfor %}

---

### Invited Talks

- **[Meta Flow Matching (MFM)](https://www.youtube.com/watch?v=-4Av5IEc_Wc)**  
  [Learning on Graphs and Geometry, 2024](https://portal.valencelabs.com/logg) 

- **DynGFN: Towards Bayesian Inference of Gene Regulatory Networks with GFlowNets**  
  [Helmholtz AI Conference, 2024 ](https://haicon24.de/)  

---
