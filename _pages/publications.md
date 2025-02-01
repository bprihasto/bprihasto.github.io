---
layout: archive
title: "Publications"
# permalink: /publications/
author_profile: true
---



EVA-ASCA: Enhancing Voice Anti-Spoofing through Attention-based Similarity Weights and Contrastive Negative Attractors
 no-Q as Conference Proceedin Proceedings - 2024 IEEE Conference on Artificial Intelligence, CAI 2024


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
