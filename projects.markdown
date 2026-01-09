---
layout: page
title: Projets
permalink: /projects/
---

{%for project in site.projects %}

---

### [ {{ project.title }} ]({{ project.url }}{{ project.permalink }})
réalisé en : {{ project.categories }}

{% endfor %}