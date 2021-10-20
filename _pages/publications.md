---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For most up to date list, see <u><a href="https://scholar.google.ch/citations?user=jPoID5gAAAAJ&hl=en">my Google Scholar profile</a>.</u>

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
