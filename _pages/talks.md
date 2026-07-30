---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

<style>
.page__meta {
  font-size: 0.95em;
  color: #333;
  margin: 0.2em 0;
}

.archive__item-excerpt {
  font-size: 0.95em;
  color: #333;
  margin: 0.2em 0;
}
</style>

Please feel free to reach out about any of the following talks or presentations.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}