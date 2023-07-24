---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
 -->

You can find the most up-to-date list of publications on [my Google Scholar profile](https://scholar.google.com/citations?user=GVoC568AAAAJ&hl=en&oi=ao).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
