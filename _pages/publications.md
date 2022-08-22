---
layout: archive
title: "Research Works"
permalink: /works/
author_profile: true
#<script src="https://bibbase.org/service/mendeley/a4e10ad6-978c-3c9d-b9c9-c903b9d27003?jsonp=1"></script> 
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h3>Other Research Works</h3>	

{% for post in site.works reversed %}
  {% include archive-single.html %}
{% endfor %}

