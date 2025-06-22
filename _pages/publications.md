---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please feel free to reach out about any of the following publications.

3. **Matthew A. Morena** and Kevin M. Short, [Cupolets: Theory and Applications](https://doi.org/10.3390/dynamics4020022), _Dynamics_, 4(2), pp. 394-424 (2024).

2. **Morena, A. Morena** and Smith, Michael, [The Euclidean Discus Toss](https://doi.org/10.1080/10511970.2023.2229811), _PRIMUS_, 33(10), pp. 1071–1090 (2023).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
