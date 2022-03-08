---
layout: page
---

list of pages

 {% for page in site.pages %}
   <li><a href="{{ page.url }}">{{ page.title }}</a></li>
 {% endfor %}
