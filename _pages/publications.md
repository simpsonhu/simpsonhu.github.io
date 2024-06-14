---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Journal Papers
======

Conference Proceedings
======

[C.1] [Matching Network Elimination in Multiband Metasurface-Structured Rectennas for Wireless Power Transfer and Energy Harvesting](http://ieeexplore.ieee.org/abstract/document/10501137). EuCAP 2024 - 2024 18th European Conference on Antennas and Propagation (EuCAP)(pp 1-4). Glasgow, UK, 17 March 2024 - 22 March 2024.
