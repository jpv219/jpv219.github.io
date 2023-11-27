---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% assign years = site.publications | map: 'date' | date: "%Y" | uniq %}

{% for year in years %}
  <h2>{{ year }}</h2>
  {% for post in site.publications %}
    {% assign publication_year = post.date | date: "%Y" %}
    {% if publication_year == year %}
      {% include styled-publication.html %}
    {% endif %}
  {% endfor %}
{% endfor %}

