---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /resume
---

<!-- 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->



{% include base_path %}

Education
======
* B.S. in Mathematics, Institut Teknologi Sepuluh Nopember - Indonesia, 2013
* M.S. in Mathematics, Institut Teknologi Sepuluh Nopember - Indonesia, 2015
* Ph.D in Computer Science, National Central University - Taiwan, 2023 

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
