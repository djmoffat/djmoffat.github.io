---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=1uqVZdQAAAAJ&hl=en">my Google Scholar profile</a>.</u>


{% include base_path %}


## Journal Publications
{% for post in site.journal reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference Publications
{% for post in site.conference reversed %}
  {% include archive-single.html %}
{% endfor %}