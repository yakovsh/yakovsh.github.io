---
# the default layout is 'page'
icon: fas fa-info-circle
order: 6
---

I have done many things professionally over the years. 
The closest thing to a resume can be found at 
[my LinkedIn profile](https://www.linkedin.com/in/yakovsh). 
Majority of my side projects can be found via 
[my consulting company’s website](https://web.impossibledreams.net). 
Open source stuff is available on [GitHub](https://github.com/yakovsh).

Within these sections you can find a variety of technology-related 
articles and other materials I have published or contributed to
over the years.

<ul>
{% for page in site.pages %}
  {% if page.tags contains "work" %}
      <li><a href="{{ page.url }}">{{ page.title | replace: "Work /", "" }}</a></li>
  {% endif %}
{% endfor %}
</ul>
