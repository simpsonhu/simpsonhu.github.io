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

[C.1] Matching Network Elimination in Multiband Metasurface-Structured Rectennas for Wireless Power Transfer and Energy Harvesting. paperurl: '[http://ieeexplore.ieee.org/abstract/document/10501137'.
