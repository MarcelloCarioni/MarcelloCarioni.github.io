---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* <b> A generalized conditional gradient method for dynamic inverse problems with optimal transport regularization </b> <br>
  Kristian Bredies, Marcello Carioni, Silvio Fanzon, Francisco Romero  <br>

  Published in Foundations of Computational Mathematics, 2022
  
  [Download Arxiv preprint](https://arxiv.org/pdf/2012.11706.pdf)

* <b> End-to-end reconstruction meets data-driven regularization for inverse problems </b> <br>
  Subhadip Mukherjee, Marcello Carioni, Ozan Öktem, Carola-Bibiane Schönlieb <br>
  
  Published in Neurips, 2021

  [Download Arxiv preprint](https://arxiv.org/pdf/2106.03538.pdf)
  
* <b> On the extremal points of the ball of the Benamou–Brenier energy </b> <br>
  Kristian Bredies, Marcello Carioni, Silvio Fanzon, Francisco Romero <br>
  
  Published in Bulletin of the London Mathematical Society, 2021

  [Download Arxiv preprint](https://arxiv.org/pdf/1907.11589.pdf)


  
Authors: 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
