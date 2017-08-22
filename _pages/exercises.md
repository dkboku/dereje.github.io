---
layout: archive
title: "Exercises"
permalink: /exercises/
author_profile: true
---

Will be updated soon
{% if author.googlescholar %}
  You can also find the exercises on <u><a href="{{author.googlescholar}}"> exercises</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
