---
title: Intro file
permalink: intro.html
---

this is a base file.

{% for doc in site.docs %}
{% if doc.section == "intro" %}
{{ doc.content }}
{% endif %}
{% endfor %}