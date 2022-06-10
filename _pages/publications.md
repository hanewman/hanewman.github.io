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
  
 **Juvenilia**
 
 An exposition I wrote on the chromatic number of string graphs in fulfillment of requirements for the Oxford M.Sc.:
 {{ site.url }}/_pages/diss.pdf
 
In the past, I have worked with Moon Duchin's Metric Geometry and Gerrymandering Group, which is a team of Boston-based mathematicians bringing mathematics and computer science methods to bear on redistricting. Here is one fun study that came out of my work with this group. 

My undergraduate Princeton senior thesis on the roots of random polynomials: 

