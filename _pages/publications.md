---
layout: archive
title: "Publications"
permalink:  /publications/
author_profile: true
---
[1] [Pradhan, Satya Prakash and Yavari, Arash, 2023. Accretion–ablation mechanics. <i>Phil. Trans. R. Soc. A.</i> 381: 20220373. 20220373.](https://arxiv.org/pdf/2307.00159.pdf) [[Download paper here](http://doi.org/10.1098/rsta.2022.0373)]([https://arxiv.org/pdf/2307.00159.pdf](http://doi.org/10.1098/rsta.2022.0373))
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
