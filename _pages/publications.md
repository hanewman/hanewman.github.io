---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Matroid-Based TSP Rounding for Half-Integral Solutions**  
  with: Anupam Gupta, Euiwoong Lee, Jason Li, Marcin Mucha, and Sherry Sarkar  
  Integer Programming and Combinatorial Optimization <a href="https://www.ipco2022.com/home"> (**IPCO 2022**) </a>  
  <a href="https://arxiv.org/abs/2111.09290"> arXiv version </a>