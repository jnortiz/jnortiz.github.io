---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Pre-prints
======
{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}


Conference publications
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
