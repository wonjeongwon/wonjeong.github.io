---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

I'll be working with Professor Kelly Musick for PAM3120 (Research Design, Practice, and Policy).
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
