---
# the default layout is 'page'
icon: fas fa-info-circle
order: 5
---

Most of the things I do professionally are somehow related to technology.
Here you can find some non-work/non-technology things about me.

<ul>
{% for page in site.pages %}
  {% if page.tags contains "personal" %}
      <li><a href="{{ page.url }}">{{ page.title | replace: "Personal /", "" }}</a></li>
  {% endif %}
{% endfor %}
</ul>
