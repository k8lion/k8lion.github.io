---
layout: archive
title: "Publications"
permalink: /publications/
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

