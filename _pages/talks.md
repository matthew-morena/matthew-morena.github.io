---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

Please feel free to reach out about any of the following talks or presentations.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
