---
layout: archive
title: "Publications"
permalink: /publications/
header:
  overlay_color: "#5e616c"
  overlay_image: "/assets/images/Ireland 2017 FIrst Week - 182.jpg"
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
