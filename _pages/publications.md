---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### This website is no longer being updated. Please visit me at [hhuiwangg.github.io](https://hhuiwangg.github.io/)!

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
