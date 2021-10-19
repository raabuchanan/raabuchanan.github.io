---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

---
# Journal Papers

{% for post in site.publications reversed %}
  {% include archive-single-no-title.html %}
{% endfor %}

---
# Conferences

{% for post in site.conferences reversed %}
  {% include archive-single-no-title.html %}
{% endfor %}
