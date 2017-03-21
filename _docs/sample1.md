---
title: sample 1
permalink: sample1.html
section: intro
myproperty: true
---

this is sample 1

{% if page.myproperty == true %}
the page has myproperty
{% elsif page.myproperty != true %}
the page does not have myproperty 
{% endif %}