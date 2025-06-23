---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please feel free to reach out about any of the following publications.

3. **Matthew A. Morena** and Kevin M. Short, [Cupolets: Theory and Applications](https://doi.org/10.3390/dynamics4020022), _Dynamics_, 4(2), pp. 394-424 (2024).

2. **Matthew A. Morena** and Michael D. Smith, [The Euclidean Discus Toss](https://doi.org/10.1080/10511970.2023.2229811), _PRIMUS_, 33(10), pp. 1071–1090 (2023).

3. **Matthew A. Morena** and Kevin M. Short, [Chaotic entanglement: entropy and geometry](https://doi.org/10.3390/e23101254), _Entropy_, 23(10), 1254 (2021).

4. **Matthew A. Morena** and Kevin M. Short, [Fundamental cupolets of chaotic systems](https://doi.org/10.1063/5.0003443), _Chaos_, 30(9), 093114 (2020).

5. Kevin M Short and **Matthew A. Morena**, [Signatures of quantum mechanics in chaotic systems](https://doi.org/10.3390/e21060618), _Entropy_, 21(6), 618 (2019).

6. **Matthew A. Morena**, Shelly Smith, and Robert Talbert, [Video Made the Calculus Star](https://doi.org/10.1080/10511970.2017.1396568), _PRIMUS_, 29(1), pp. 43-55 (2019).

7. **Matthew A. Morena** and Kevin M. Short, [On the potential for entangled states between chaotic systems](https://doi.org/10.1142/S0218127414500771), _International Journal of Bifurcation and Chaos_, 24(104), 1450077 (2014).

8. **Matthew A. Morena** and Kevin M. Short, [Controlled transitions between cupolets of chaotic systems](https://doi.org/10.1063/1.4862668), _Chaos_, 24(1), 013110 (2014).

9. **Matthew A. Morena** and John E. Franke, [Predicting attenuant and resonant 2-cycles in periodically forced discrete-time two-species population models](https://doi.org/10.1080/17513758.2012.710338), Journal of Biological Dynamics, 6(2), pp. 782-812 (2012).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
