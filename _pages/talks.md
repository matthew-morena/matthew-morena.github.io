---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

<style>
.archive__item {
  margin-bottom: 1.5em;
  padding: 0;
}

.archive__item-title {
  margin-bottom: 0.3em;
}

.archive__item-excerpt {
  font-size: 1em;
  color: #333;
  margin-top: 0.3em;
  margin-bottom: 0;
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
