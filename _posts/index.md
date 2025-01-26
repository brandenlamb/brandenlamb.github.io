---
title: Projects
---

{% for page in site.pages %}
  <h2> {{ page.title }} </h2>
  <p> {{ page.description }} </p>
{% endfor %} 
